# Clean-and-Analyze-Employee-Exit-Surveys

In this project, we'll work with exit surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia. 

The `DETE exit survey data` is available from: https://data.gov.au/dataset/ds-qld-fe96ff30-d157-4a81-851d-215f2a0fe26d/details?q=exit%20survey. <br>
The original `TAFE exit survey data` is no longer available. We've made some slight modifications to the original datasets to make them easier to work with, including changing the encoding to UTF-8 (the original ones are encoded using cp1252.)

Learning source: `DataQuest`

### In this project, we will try to answer the following questions:

1. Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
2. Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

Below is a preview of a couple columns from `dete_survey.csv`:

- `ID`: An id used to identify the participant of the survey.
- `SeparationType`: The reason why the person's employment ended.
- `Cease Date`: The year or month the person's employment ended.
- `DETE Start Date`: The year the person began employment with the DETE.

Below is a preview of a couple columns from `tafe_survey.csv`:

- `Record ID`: An id used to identify the participant of the survey.
- `Reason for ceasing employment`: The reason why the person's employment ended.
- `LengthofServiceOverall`: Overall Length of Service at Institute (in years): The length of the person's employment (in years).
