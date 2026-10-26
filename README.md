# merry-opal-mini

Django · AWS · Kubernetes

学习用的示例项目

## 用法

```bash
cat data.txt | ./run.sh
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 安装

```bash
git clone https://github.com/USER/merry-opal-mini.git
cd merry-opal-mini
chmod +x run.sh
```

## License

MIT
