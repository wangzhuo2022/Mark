前言：[Typora](https://so.csdn.net/so/search?q=Typora&spm=1001.2101.3001.7020)是一款牛逼的编辑器，这应该是大家公认的吧，不过也有人觉得并非如此，毕竟，它就像八九十年代的大哥大，你只有带着你的电脑才能看到你自己写的笔记，如何拉屎的时候也可以自我陶醉在自己的文章中呢，那GitHub全球最大的代码托管网站就是不二之选。不会21世纪还有有人不知道GitHub。哈哈，调皮一下！我们开始搭建超级笔记本吧

### 1、前提准备

```null
Typora + GitHub安装
```

### 2、创建[GitHub](https://so.csdn.net/so/search?q=GitHub&spm=1001.2101.3001.7020)项目

```null
略
```

### 3、在本地创建同名文件夹

1）如下图找到路径，然后检查文件的状态，再激活文件夹，使其产生一个git类型的文件夹

![](https://img-blog.csdnimg.cn/20210602220533332.png)

![](https://img-blog.csdnimg.cn/20210602220548308.png)

### 4、将本地文件与GitHub项目关联

![](https://img-blog.csdnimg.cn/20210602220654887.png)

### 5、上传文件到GitHub

1）如果文件夹为空，创建文件才可以上传

2）文件夹不为空，

*   执行git status检查文件夹状态
    
*   git add .注意，这里的空格+句号
    
*   git commit -m "develop\_note"链接GitHub文件
    
*   git push origin master执行上传操作
    

3）遇到问题

![](https://img-blog.csdnimg.cn/20210602220728505.png)

      解决方案：

![](https://img-blog.csdnimg.cn/20210602220745350.png)

### 6、大功告成

```null
以后有新的笔记，直接右键Git Bash Here>>>输入git push origin master就可以实时上传笔记了
```

业精于勤，荒于嬉；行成于思，毁于随

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