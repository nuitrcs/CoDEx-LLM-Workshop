# CoDEx-LLM-Workshop
Materials for the workshop "How to code with LLMs" - CoDEx 2024.

The workshop slides are in the file [LLM_Codex_Workshop](https://github.com/nuitrcs/CoDEx-LLM-Workshop/blob/main/LLM_Codex_Workshop.pdf), and the prompt engineering summary sheet is in [prompt_engineering_cheat_sheet](https://github.com/nuitrcs/CoDEx-LLM-Workshop/blob/main/prompt_engineering_cheat_sheet.pdf).

**Hands-on Exercise**

Here are the links to the different chatbots we will use in the hands-on exercise:
* (A-H): OpenAI's [ChatGPT](https://chat.openai.com/).
* (I-Q): Microsoft's [Copilot](https://www.bing.com/chat) in Bing.
* (R-Z): Google's [Gemini](https://gemini.google.com).

PART 1:

Use an LLM to generate code to determine **which country consumed the least meat per capita in 2020**.
* Use the data hosted [here](https://raw.githubusercontent.com/emiliolehoucq/trainings/main/data/oecd_data.csv).
* Run the code yourself to make sure it works.
* This is what the columns mean:
  * LOCATION is the country.
  * SUBJECT is meat type (beef, pig, poultry, sheep).
  * MEASURE is the metric reported.
    * KG_CAP - kilograms per capita.
    * THND_TONNE - thousand tonnes.
  * TIME is the year.
  * VALUE is the value for the indicator.
 
PART 2:

Was exercise 1 too easy? Try this!

**Which country has the least annual meat consumption per capita the most years between 2000 and 2020?**

For example, if country X consumed the least for 7 yrs, and country Y consumed the least for 13 years. Country Y would be the answer.


