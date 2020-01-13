# Text2HBM Textual Instructions

This folder contains textual descriptions and the corresponding plans. The descriptions are meant for generating planning operators from texts, while the plans are used to test the generated models.


# 83 descriptions:

- Cake -> 10 descriptions

- Chicken -> 10 descriptions

- Cookies -> 14 descriptions

- French toast -> 14 descriptions

- House water filter -> 2 descriptions

- Movie tickets -> 2 descriptions

- PC cooler -> 1 description

- Portable air conditioner -> 4 descriptions

- Sushi -> 13 descriptions

- Tour steps -> 5 descriptions

- Vacation plan -> 3 descriptions

- Washing machine -> 5 descriptions


# Folder structure: 

- -> "Type of instruction"

	--> Plans
        
	--> Raw_Data
        
	--> Refined_Text
        
	--> Refined_Text2
	

Folder "Plans" contains the plans corresponding on the refined text. As the descriptions were collected by two people, in some of the folders there is additional folder "Refined_Text2". If this folder exists for the given instruction, then the plans are based on "Refined_Text2". Each step in a plan has the form Time,*,(action object object) (e.g. 1,*,(take cup table)). The time indicates the start time of the action, * indicates that the actions is a new actions, and the concrete action with the involved elements of the environment is in brackets. 

Folder "Raw_Data" contains the original instructions. 

Folder "Refined_Text" contains a refinement of the original instructions from folder "Raw_Data". This refinement consists of making the sentences shorter, with only one verb per sentence. The sentences also start with a verb in imperative form. 

Folder "Refined_Text2" contains a refinement of the texts in folder "Refined_Text". As the data was collected by two persons, for some instructions the intermediate refinement was not kept, thus the final refinement is in folder "Refined_Text".  	

#License

This data is free to use for any purpose. If you write a paper using the data, please send an email to kristina.yordanova@text2hbm.org giving the citation. Please also include the following text in your acknowledgments section:

The data used in this paper was obtained from https://github.com/stenialo/Text2HBM and the data collection was funded by the German Research Foundation (DFG), grant number YO 226/1-1.
