# BERT-base-10fold
采用10折交叉验证的BERT文本情感分析
该项目基于BERT的base架构下对IEMOCAP的文本情感进行分析  
运行后的F1分数大概在71%  
附一张某次运行完10折的混淆矩阵
![image](https://github.com/shock1ng/BERT-base-10fold/assets/125559105/426b14a3-4081-4bfd-beb6-5c516fb91e8c)


# 项目准备：  
1.从Hugging Face上下载BERT-base的全部文件  
2.需要对IEMOCAP的全部文件进行解压  
3.自备可以正常运行的环境  

# 项目运行步骤  
1.特征生成.py  
2.data_pp.py  
3.train

