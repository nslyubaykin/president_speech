# Finetuning GPT2 to answer questions like Vladimir Putin

This repository [implements](https://github.com/nslyubaykin/president_speech/blob/master/president_speech.ipynb) GPT2 finetuning on Vladimir Putin question-answer data parsed from official Kremlin 
transcripts site. Rusilting dataframe contains 5526 question-answer pairs (attached to this repository) and was used to finetune SberAI ru-GPT2-Meduim for 3 epochs.

Model sample Outputs:

QUESTION: Каковы, на ваш взгляд, перспективы использования паукообразных роботов в сельском хозяйстве?

ANSWER:   Вы знаете нашу позицию. Мы считаем: и мы не против применения роботизированных систем для решения задач сельского хозяйства – это тоже часть нашей позиции по этому вопросу; но только при условии соблюдения принципов промышленной политики страны с учетом интересов фермеров-производителей сельскохозяйственной продукции либо ее потребителей (это касается как России вообще так же стран СНГ).  

QUESTION: Каким будет 2023 год?

ANSWER:   Это сложный вопрос. Я думаю, что мы все должны быть готовы к тому времени и в состоянии решить те задачи развития страны на перспективу – это прежде всего развитие экономики; социальной сферы: здравоохранения (мы сейчас говорим о здравоохранении), образования всех уровней с тем чтобы обеспечить людей качественными услугами по доступным ценам для населения Российской Федерации как минимум до конца этого года или даже раньше).  

QUESTION: Оказавшись перед Путиным, что вы ему скажете?

ANSWER:   Я скажу: «Владимир Владимирович! Вы знаете мою позицию. Она заключается в том числе и во введении визового режима между нашими странами».  
