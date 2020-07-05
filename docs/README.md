## tkitMatch匹配函数合集



```
from tkitMatch import Match

```
#### 匹配成对标签
匹配成对标签内的文本比如'<a helf="www.baidu.com" title="河南省">你好</a>' 或者div这种

```
title = '[KG]趣秘[/KG][KG]乌白舞，[UNK]的,亲”克扬语她[S]部曲，作者，演剧恋[S]首歌手[S]所属系些罗齐体她性》是剧聊为作者[S]'
S=Match()
kg=S.matching_pairs(title,"KG")
print(kg)
# ['趣秘']

```