# Supplement B    Questionnaire Design

## Background

Mobile vendors develop their customized Android versions based on the Android Open Source Project (AOSP) led by Google. As the AOSP releases new versions frequently, vendors need to periodically carry out the Android upgrade. Both the AOSP and Android variants independently undergo extensive and complex modifications. Consequently, Android upgrades often lead to compatibility issues and conflicts. To systematically define, study, and resolve these conflicts during the Android upgrade process, we kindly request you to dedicate 15 minutes to complete the following survey. Your participation will greatly assist us in gathering insights. This survey will be anonymized, focusing solely on trends and improvement suggestions.

## Distribution of Respondents' Attributes

| Attribute                                             | Specific Categories                                          |
| :---------------------------------------------------- | ------------------------------------------------------------ |
| Android Business Modules                              | Includes 76 different modules such as SystemUI, Bluetooth, Camera, etc. |
| Roles                                                 | Includes Project Manager, Architect, Developer, Maintenance Personnel |
| Level of Work Experience                              | Includes within 1 year, within 5 years, within 10 years, and over 10 years |
| Number of Participations in Android Upgrade Processes | Includes within 5 times, within 10 times, within 50 times, and over 50 times |
| Total Number of Conflicts Resolved                    | Includes within 10, within 100, within 1000, and over 1000   |

## Questionnaire Questions Design

==The complete Questionnaire can be found in [Questionnaire Questions](./Questionnaire%20Questions.md  )==

This questionnaire primarily covers the experiences and challenges faced by Android developers during the conflict resolution process in Android upgrades. It includes aspects such as the modules they are responsible for, the number of upgrades they have participated in, their work experience, reasons of conflicts, conflict resolution, technical challenges, use of tools, team collaboration, stress levels, and experience sharing.

*►[Personal Information]*

- **Android Business Modules**: Which features or modules are you primarily responsible for developing? [Open-ended Question Q1]
- **Number of Participations in Android Upgrade Processes**: How many versions have you participated in conflict resolution for system upgrades? [Single-select Question Q2]
- **Level of Work Experience**: How many years of Android work experience do you have? [Single-select Question Q3]
- **Total Number of Conflicts Resolved**: How many conflicts have you resolved in total? [Single-select Question Q4]

*►[Conflict Causes and Types]*

- **Conflict Causes**: 
   1. Based on your experience, what do you think are the causes of conflicts? [Open-ended Question Q10]
   2. How often do you review Google commits and self-developed commits when analyzing the causes of conflicts? [Single-select Question Q14]

- **Conflict Types**:
   1. What types of conflicts have you resolved during the conflict resolution process? [Multiple-answer Question Q5]
   2. Which specific types of conflicts are more difficult to handle? [Multiple-answer Question Q16]

*►[Conflict Resolution]*

- **Conflict Resolution Process and Time**:
   1. How many steps does your process for resolving a single conflict in codex involve? (Your understanding of conflicts is important for tool development and training) [Open-ended Question Q6]
   2. How many steps does your process for resolving a single conflict involve? What is the time distribution for each step? [Open-ended Question Q12]
   3. How long does it typically take to resolve a complex conflict? Does it require assistance from other engineers, such as voice models or conflict change commits? [Open-ended Question Q13]
   4. What is the total time allocated for your conflict resolution tasks? [Single-select Question Q11]
- **Conflict Resolution Methods**:
   1. Which conflict resolution methods do you use more frequently? [Multiple-answer Question Q7]
   2. How do you handle conflict code that repeatedly appears in multiple versions? [Multiple-answer Question Q9]
- **Technical and Tool Challenges**:
   1. What technical challenges do you usually encounter when resolving merge conflicts? [Open-ended Question Q15]
   2. What tools or resources do you typically use when handling conflicts? [Open-ended Question Q21]
   3. Have these tools effectively helped you reduce conflict resolution time or improve efficiency? [Open-ended Question Q22]
   4. When using existing tools, what issues do you think still need improvement or optimization? [Open-ended Question Q28]
   5. Based on your experience, what methods or tools do you think could improve the current conflict resolution process? [Open-ended Question Q27]
- **Familiarity with Historical Solutions**:
   1. Resolving conflicts requires understanding Google's historical solutions. Please assess your familiarity with these solutions on a scale of 1-10. (1 - Least familiar, each solution needs to be understood from the basic architectural principles; 6 - Need to individually review commits and understand historical solutions; 10 - Very familiar, no need to review commits, and already know the solution) [Single-select Question Q17]
   2. Resolving conflicts requires understanding self-developed project historical solutions. Please assess your familiarity with these solutions on a scale of 1-10. (1 - Least familiar, each solution needs to be understood from the basic architectural principles; 6 - Need to individually review commits and understand historical solutions; 10 - Very familiar, no need to review commits, and already know the solution) [Single-select Q18]
   3. Resolving conflicts requires understanding Google's new upgrade solutions. Please assess your familiarity with these solutions on a scale of 1-10. (1 - Least familiar, each solution needs to be understood from the basic architectural principles; 6 - Need to individually review commits and understand historical solutions; 10 - Very familiar, thorough initial commit analysis, can quickly recall issues) [Single-select Question Q19]

*►[Conflict Impact Analysis]*

- Does the conflict resolution process involve code or files outside the conflict blocks? [Single-select Question Q8]

*►[Other]*

- **Team Management**:
   1. During the conflict resolution process, which team members (e.g., other developers, testers, project managers) do you usually need to collaborate with? [Open-ended Question Q23]
   2. Is the collaboration effective, and is there room for improvement? [Open-ended Question Q24]
- **Stress and Support**:
   1. What kind of emotional pressure do you usually feel during the conflict resolution process? [Open-ended Question Q25]
   2. Are there any specific supports or strategies that help you cope with project-related stress? [Open-ended Question Q26]
- **Experience Sharing and Suggestions**:
   1. What suggestions do you have for new developers to help them resolve such issues more effectively? [Open-ended Question Q29]
   2. Can you share an experience of particularly difficult or successful conflict resolution? [Open-ended Question Q30]
   3. What important lessons have you learned from these experiences? [Open-ended Question Q31]

*►[Follow-up]*

1. Would you be willing to accept a follow-up interview? (We can discuss the evolution of upgrades together, making future upgrades smoother) [Single-select Question Q20]






