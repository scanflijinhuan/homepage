# homepage
只用recyclerview实现复杂首页布局，布局随增减数据动态显示

效果图：

![image](https://github.com/magicbaby810/homepage/blob/master/imgs/s1.jpg)

![image](https://github.com/magicbaby810/homepage/blob/master/imgs/Screenshot_20170612-145631.png)

删除第二层布局
```java
ArrayList<HomepageItemEntity> bList = new ArrayList<>();
        for (int i = 0; i < 4; i ++) {
            HomepageItemEntity bEntity = new HomepageItemEntity();
            bEntity.title = "sdad";
            bEntity.url = "https://www.baidu.com/";
            bEntity.img = "";
            bList.add(bEntity);
        }

//homepageEntity.B = bList; 仅注释此行数据即可，具体步骤是在你的接口中不给homepageEntity.B赋值。
```
//以下同理

![image](https://github.com/magicbaby810/homepage/blob/master/imgs/Screenshot_20170612-145723.png)

删除第三层布局
```java
ArrayList<HomepageItemEntity> cList = new ArrayList<>();
        for (int i = 0; i < 4; i ++) {
            HomepageItemEntity cEntity = new HomepageItemEntity();
            cEntity.title = "sdad";
            cEntity.url = "https://www.baidu.com/";
            cEntity.img = "";
            cList.add(cEntity);
        }
//homepageEntity.C = cList;
```

![image](https://github.com/magicbaby810/homepage/blob/master/imgs/Screenshot_20170612-145747.png)

删除第四层布局
```java
ArrayList<HomepageItemEntity> dList = new ArrayList<>();
        for (int i = 0; i < 8; i ++) {
            HomepageItemEntity dEntity = new HomepageItemEntity();
            dEntity.title = "sdad";
            dEntity.url = "https://www.baidu.com/";
            dEntity.img = "";
            dList.add(dEntity);
        }
//homepageEntity.D = dList;
```
![image](https://github.com/magicbaby810/homepage/blob/master/imgs/Screenshot_20170612-145816.png)