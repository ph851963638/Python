# Python


Python 变量   输出和输入   数字   字符串
2.1  变量使用
    变量以及类型
    1、变量的定义
    
    
    2、标示符的命名规则
    由字母、下划线和数字组成，且数字不能开头
    标识符区分大小写
    命名规则和方法 
    提高代码可读性
    驼峰命名法
    userName   首字母小写后面字母大写
   
 
2.2  input 

name=input('请输入你的姓名')
print(name)


2.3 Pyhthon数字类型介绍
整型        int     
浮点型      float 
长整型      longof
type(of) 
print（type(1)）
class int

内健函数
abc(x) 取x的绝对值
rounds（number,ndigits）

2.4  python 字符串类型
字符串定义
   有序的 不可更改的，以引号包围的序列，
   双引号或者单引号中的数据，就是字符串
引号：
单引号  '
双引号"  "   
三单引号' ' '    多用于代码的注释
三双引号" " "   多用于代码的注释


#打印字符串
print('my name is %s'%('for'))

#打印浮点数
print('his height is %.2f m' %(1.80))
    
#包头不包尾，字符串截图    
name='while'
print(name[1:3])

[start:end:step] start 默认值为0；end 默认值为字符创结束元素  step 默认值为1

str_test=‘hello,world’
print(str_test[0:7:2])
print(str_test[0:7:-1])反转
print(str_test[0:7:-2])间隔为1
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    python虚拟机
    1、垃圾回收机制
    当一个常量被生成，会占用一份内存，这时候如果有变量指向该常量，那么该常量的引用计数为1，python虚拟机规定，当一个常量的引用计数为0，也就是没有该变量指向的时候，该常量占用的内存会被回收。
    
    
    
    
    
    
