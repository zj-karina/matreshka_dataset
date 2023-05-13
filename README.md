# matreshka_dataset

![IMG_6774](https://github.com/zj-karina/matreshka_dataset/assets/70880156/1842445b-4257-47de-a308-677239c5427c)
(image generated by Kandinsky-2.1 neural network)

Russian dialogues, the persona of the first interlocutor, and a summary of the dialogue generated by GPT-3.5, starting with the first phrase given in the prompt.

The matreshka dataset is a multi-tasking dataset, you can use it for the task of summarizing a dialogue or generating a dialogue. Contains life dialogues and is also filled with facts about the world. The dataset was going to give the interlocutor a human manner of communication.

After generation, some data contained a format that did not match the request, so we stripped the data with regular expressions. Next, we checked for the correct data type in each line, and changed to the correct format if necessary.
