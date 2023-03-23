# pyftsubset

使用[fonttools](https://github.com/fonttools/fonttools)压缩字体的一个模板

1. 安装[python3.8+](https://www.python.org/)
2. 安装[fonttools](https://github.com/fonttools/fonttools)
```sh
pip install fonttools
```
3. 参考以下模板压缩所需字体文件
```sh
pyftsubset ./SourceHanSans_CN_Regular.otf --output-file=./SourceHanSans_CN_Regular_3500.ttf --text-file=./cn3500
```
