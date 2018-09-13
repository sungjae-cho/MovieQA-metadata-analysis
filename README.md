# MoviewQA-metadata-analysis
To analyze the metadata of the MoviewQA data set

## 1. Definitions
* __MovieQA__ consists of videoQA and textQA. __VideoQA__ has some 'video clips' but __textQA__ has no 'video clips.'
* A __sentence__ ends with a lowercase character or number, and '.', '!' or '?'. In the data set, someone's saying is interrupted by another's saying that is a full sentence. In that case, I assume that their sayings are just one sentence. 

## 2. Target

* Average words per question = len(words in all questions) / len(questions) = 9.585788827501535 = 9.5858
* Average words per answer = len(words in all answers) / len(answers) =  5.339717618170657 = 5.3397
* Sentences in subtitles = 745416
* Average words per subtitle sentence = len(words in all subtitles) / len(subtitles) = 7.704980842911877 = 7.7050