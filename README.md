# apkscan-pkid-v2.0

**欢迎大家提交规则，或留意无法识别的加固app，争取每季度更新**

更新记录：

​	20220325 新添 腾讯乐固（VMP） apk加固检测

​	20220427 修改逻辑 优化输出，修复二级子目录检测不到的bug



原工具是2018年的了，没找到新版本，也没有源码没法基于jar修改（懒得反编译重写java）

工具查不了腾讯云加固

![image-20210629095251291](image-20210629095251291.png)

把里面的规则扣出来，用py3重新写了，py脚本也方便大家自己添加规则

![image-20210629095138615](image-20210629095138615.png)

20220427修改，优化了一下结果输出



![check](check.png)

无输入的help提示

![help](help.png)
