# SDL2-for-android
# 工程目录：
            SDL2-2.0.5
                        ./Android.mk                       --⑶
                        ./android-project
                                    ./jni
                                    ./src/Android.mk       --⑴
                                    ./Android.mk           --⑵
                                    ./Application.mk
                                    
</p>
--⑶ Android.mk 用来编译SDL2-2.0.5工程的mk文件，里面写好了编译代码。可以编译出(SDL2)静态或者动态库。</p>
--⑵ Android.mk 用来编译android-project工程的mk文件。可以编译出(main)的动态库。</p>
--⑴ Android.mk 用来编译src下自己写的代码的编译文件。</p>

## 移植步骤
1.在android-project/jni 下新建SDL文件。</p>
2.将SDL2-2.0.5目录下的src和include目录拷贝到android-project/jni/SDL目录下。</p>
3.将SDL2-2.0.5目录下的Android.mk文件拷贝到android-project/jni/SDL目录下。</p>
4.编译。

### 相关链接
源码：http://www.libsdl.org/ </p>
博客：忘了
