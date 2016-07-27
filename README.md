# h5upload
js多图上传带预览功能控件
#基础用法
```
$("#inputfiles").h5upload();
```
#高级用法
```
$("#inputfiles").h5upload({
  exts: ['jpg', 'gif', 'png', 'jpeg'], 
  max: 1, 
  size: 3145728,
  del: true, 
  name: 'uploadfile' //input name
});
```
