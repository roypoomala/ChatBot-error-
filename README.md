# ChatBot-error-
Traceback (most recent call last):   File "D:/Practice/PyCharm2019/main.py", line 1, in &lt;module>     from chatterbot import ChatBot   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\__init__.py", line 4, in &lt;module>     from .chatterbot import ChatBot   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\chatterbot.py", line 2, in &lt;module>     from chatterbot.storage import StorageAdapter   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\storage\__init__.py", line 1, in &lt;module>     from chatterbot.storage.storage_adapter import StorageAdapter   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\storage\storage_adapter.py", line 3, in &lt;module>     from chatterbot.tagging import PosHypernymTagger   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\tagging.py", line 4, in &lt;module>     from chatterbot.tokenizers import get_sentence_tokenizer   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\tokenizers.py", line 4, in &lt;module>     from chatterbot.corpus import load_corpus, list_corpus_files   File "D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot\corpus.py", line 5, in &lt;module>     from chatterbot_corpus.corpus import DATA_DIRECTORY ImportError: cannot import name 'DATA_DIRECTORY' from 'chatterbot_corpus.corpus' (D:\Practice\PyCharm2019\venv\lib\site-packages\chatterbot_corpus\corpus.py)  Process finished with exit code 1
