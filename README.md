# rt_demo
A html script to obtain reaction time to sound/speech signals


# Working:
Everything happens in the HTML file simple_rt_speech.html. It contains some simple HTML javascript-ing.
1. Obtains the list of audio files from: ./data/rtSample/file_list.txt to ob
2. Obtain the file name and the ground truth change instant for each file and stores these in file_set_test and files_set_key variables, respectively.
3. On pressing Load 1 and 2 are carried out.
4. On pressing M the keyDownTextField() function is called to obtain the reaction time.
