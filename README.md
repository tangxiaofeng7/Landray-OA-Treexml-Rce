# Landray OA treexml.tmpl script 远程代码执行漏洞

### 声明
本程序仅供于内部自查使用，请使用者遵守《中华人民共和国网络安全法》，勿将此脚本用于非授权的测试，脚本开发者不负任何连带法律责任。

### 批量检测
```
./nuclei -t landray-oa-treexml-rce.yaml -l url.txt
```
### 效果
![result](./img/result.png)