#REQUIREMENTS

INTRODUCTION: The Electricity Bill calculator project is the application based mini project, which is used to predict the electricity bill of next month by taking input of appliance or load used. The tool used for writing the code in this project is visual studio code. This project has multi file and multiplatform approach (Linux and Windows).

#RESEARCH

People who don’t have technical knowledge of calculating electricity bill can use this application to predict electricity bill of upcoming months, however, the defining features of an electricity bill calculator include:
    ->power rating of all loads
    ->total load calculation
    ->unit consumed per day
    ->units consumed per month

High-end electricity bill calculators generally include:
    ->Electricity bill calculation in urban areas
    ->Electricity bill calculation in rural areas
    ->Bill calculation based on units consumed

Design and testing operations of electricity bill calculator using unit testing algorithm.

High Level Requirements:
#Electricity bill calculation at Urban areas
HL01 - Electricity bill calculation at Urban areas if(units<30) -> Implemented
HL02 - Electricity bill calculation at Urban areas if(units>30 && units <100) -> Implemented
HL03 - Electricity bill calculation at Urban areas if(units>101 && units <200) -> Implemented
HL04 - Electricity bill calculation at Urban areas if(units<200) -> Implemented

#Electricity bill calculation at Rural areas
HL05 - Electricity bill calculation at Rural areas if(units<30) -> Implemented
HL06 - Electricity bill calculation at Rural areas if(units>30 && units <100) -> Implemented
HL07 - Electricity bill calculation at Rural areas if(units>101 && units <200) -> Implemented
HL08 - Electricity bill calculation at Rural areas if(units<200) -> Implemented

Low Level Requiremnets:
LL01_HL01 - Calculates electricity bill at rural areas -> Implemented
LL02_HL02 - Calculates electricity bill at urban areas -> Implemented
LL03_HL03 - Calculates total load at domestics places -> Implemented
LL04      - Calculates total unit consumed at domestics places -> Implemented