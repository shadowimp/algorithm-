```python	
# 注意lambda返回值是一个元祖
sorted(person,key=lambda x: (x.age, x.height)) 


对于一个三元组的list用默认的sorted，结果是先按照第一个字段升序，在第一个字段相同的情况下按照第二个字段升序，在前两个字段都相同的情况下按照第三个字段升序。

key=lambda x: (-x[0], x[1]) # 优先对x[0] 降序排列，然后对x[1] 进行升序排列


res_dic = {}
for res_line in res:
    res_line = str(res_line)
    res_dic[res_line] = res_dic.get(res_line,0) + 1 
    
    
res_uniq = []
for item in res_dic.keys():
    item = eval(item)
    res_uniq.append(item)
    
    
    
# os 检测是否有目录下有    
if not os.path.exists(output_home):
    logger.info('Output path does not exists and created.')
    os.makedirs(output_home)
    
在python中运行linux脚本
os.system('go run hash_code.go >> word_hash.txt')
返回0表示执行成功,返回其他代表失败

        
# python 全局变量
在函数内使用 global


保留两位小数
n = 3.14159
print('%.2f'%n)
>> 3.14

word = "apple"
print(f"word:{word}")


# -*- coding:utf-8 -*-


import os
os.remove(temporary_filepath)

import io
# 限定读的字符数
size = 100
with open('brandname.csv','r') as f:
    lines_100 = io.StringIO(f.read(size))
for line in lines_100:
    print(line)
```



str.lower( ) # 字符串大写变小写

### flask

```python
from flask import Flask, jsonify

app = Flask(__name__)

@app.route('/index')
def index():
    return jsonify(msg='hello world')

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=8000)


```



which python #看目前使用的什么python环境





#### python get ip 地址

```python
import socket 
hostname = socket.gethostname()
ip = socket.gethostbyname()
```





```
which python #查看当前的python环境

pip show numpy #查看python库信息




```



Non-ASCII character '\xe5' in file word2vec_api.py on line 1, but no encoding declared 报错

```python
首行附加：
#!/usr/bin/python
# -*- coding: utf-8 -*-


```







