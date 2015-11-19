#### GPUImageFiltersCamera
感谢BradLarson/GPUImage的分享 https://github.com/BradLarson/GPUImage

时间紧迫目前提交的GPUImageFiltersCamera为demo版本，欢迎大家指点交流。 \<br>
由于有拍照功能项目所以需要真机测试。\<br>
如果程序运行时在[[[GPUImageContext sharedImageProcessingContext] context] renderbufferStorage:GL_RENDERBUFFER fromDrawable:(CAEAGLLayer*)self.layer];
出现EXC_BAD_ACCESS。 \<br>
需要修改Product->Scheme->Edit Scheme->Options->GPU Frame Capture 选择 Disabled。\<br>

#### 功能介绍
模仿Filckr的照相功能实现了： \<br>
1.实时滤镜 \<br>
2.相机基本功能：拍照，对焦，前后摄像头转换，闪光灯。\<br>

