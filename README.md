# AI 小票识别 MVP 移动端原型

本仓库当前原型入口：

- `index.html`
- `pdf-report-preview-prototype.html`：TrackEasy 溯源获取质检报告方案原型

原型覆盖店主端移动流程：拍照或从相册上传小票、最多上传 3 张、上传完成后 AI 识别、识别结果确认/修改、规则校验、确认提交。

本地预览：

```bash
python3 -m http.server 5173
```

然后访问：

```text
http://localhost:5173/
http://localhost:5173/pdf-report-preview-prototype.html
```
