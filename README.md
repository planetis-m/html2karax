# html2karax
Convert static html to Karax single page application or server sider rendering.Use https://github.com/gogolxdong/karax

把静态html转换为Karax单面应用或服务端渲染，使用https://github.com/gogolxdong/karax


## Usage
nim c -r html2karax.nim tut1
把tut1.html转换成tut1karax.nim

nim c -r html2karax.nim tut2
把tut2.html转换成tut2karax.nim

nim c -r html2karax.nim tut3
把tut3.html转换成tut3karax.nim

nim c -r html2karax.nim manual
把manual.html转换成manualkarax.nim

nim js tut1karax.nim
把tut1karax.nim编译成js，以此类推。

Open browser and access html accordingly.
通过浏览器访问相应的html文件
