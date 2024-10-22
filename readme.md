# java学习笔记

> 前提：安装到java环境，配置不在此进行展开。道阻且长，加油

[学习视频](https://www.bilibili.com/video/BV17F411T7Ao?spm_id_from=333.788.player.switch&vd_source=4046650f4b6e75ab86067f7a5a418626&p=8 "学习视频")

## HelloWorld案例

* 新建HelloWorld.java文件

```Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
    // This is a comment
}
```

* 编译文件(执行命令后生成HelloWorld.class文件)
  ```shell
  javac HelloWorld.java
  ```
* 运行程序
  ```shell
  java HelloWorld
  ```
