#优势
3d旋转GrallyView，继承FrameLayout
支持自动旋转
可直接在xml添加元素即可添加列数据。无需编写代码添加
优良的兼容性，和尺寸控制

##如何使用？
`
 <com.cry.animation.LoopView
        android:id="@+id/loopview"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:gravity="center_vertical"
        >
  <!--  此处添加你的布局元素，可以用layout包裹 --!>
       <ImageView
         android:layout_width="130dp"
         android:layout_height="20dp"
         android:scaleType="fitXY"
         android:paddingLeft="20dp"
         android:paddingRight="20dp"
         android:src="@drawable/image_shader"/>
       <ImageView
                android:layout_width="130dp"
                android:layout_height="20dp"
                android:scaleType="fitXY"
                android:paddingLeft="20dp"
                android:paddingRight="20dp"
                android:src="@drawable/image_shader"/>
       <ImageView
                android:layout_width="130dp"
                android:layout_height="20dp"
                android:scaleType="fitXY"
                android:paddingLeft="20dp"
                android:paddingRight="20dp"
                android:src="@drawable/image_shader"/>
 </com.cry.animation.LoopView>
 `
###问题反馈和联系方式
qq:347284221<br />
邮箱:zhuxiujia@qq.com<br />
![ABC](device-2015-05-22-100146.png)