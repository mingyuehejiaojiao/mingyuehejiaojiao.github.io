---
实验吧Bin100(ebCTF 2013)wp
---



##拿到题目之后，可以看出这是一个通过判断得出结果的程序。


1. 打开程序![1.png](https://upload-images.jianshu.io/upload_images/17587464-7109c844a42f02b1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
2. 2. 可知，要得到flag就要掷得所需数字用吾爱破解打开文件，得到如图![2.png](https://upload-images.jianshu.io/upload_images/17587464-c597324b46bf50c8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
3. 3. 右键 查找 所有参考文本就会看到如下![3.png](https://upload-images.jianshu.io/upload_images/17587464-a165a3e4225c3b11.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)![4.png](https://upload-images.jianshu.io/upload_images/17587464-c0eb3cc0ca2a8815.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
4. 4. 由程序可知 要得到flag就要掷得3 1 3 3 7而You rolled a three! good! 是一个判断一共有五处将每一处判断都改为nop![5.png](https://upload-images.jianshu.io/upload_images/17587464-48d41572f2839ef5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
5. 5. 修改之后 右键 复制到可执行文件全部修改 保存为新文件![6.png](https://upload-images.jianshu.io/upload_images/17587464-8abb640724293b81.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
6. 6. 打开程序 回车五次没有出现错误ctrl+f8 出现程序![7.png](https://upload-images.jianshu.io/upload_images/17587464-d67935c048738932.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
7. 7. 接着回车 得到flag![8.png](https://upload-images.jianshu.io/upload_images/17587464-fd5d6db63677e849.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
8. 这样之后，就得到了我们要的flag。即ebCTF{64ec47ece868ba34a425d90044cd2bec}

