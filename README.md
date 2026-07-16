# RVC Models

RVC 模型合集。模型文件不直接提交到 Git 历史中，实际下载文件放在 GitHub Releases 附件中。

## 使用限制

本仓库中的模型仅供二次创作、学习研究与非商业用途使用。

- 不得用于任何商业用途。
- 不得使用该模型制作、传播违反法律法规的内容。
- 不得用于冒充他人、诈骗、骚扰、诽谤、侵权或其他损害他人权益的用途。
- 使用者需自行承担因下载、传播和使用模型产生的一切责任。

## 下载方式

请在本仓库的 Releases 页面下载对应角色的 zip 文件。每个 zip 内一般包含：

```text
中文角色名/
  模型.pth
  索引.index
```

部分模型可能没有匹配到索引文件；具体情况见 `MODEL_LIST.md` 或 `manifest.csv`。

Release attachments use numbered filenames such as `rvc-model-001.zip`; use `release_assets.csv` or `RELEASE_ASSETS.md` to map them back to the original Chinese zip names.

## 文件说明

- `模型.pth`：RVC 权重模型。
- `索引.index`：RVC 检索索引。
- `索引-2.index` 等：同一模型匹配到多个索引时的附加索引。

## 清单

- [模型清单](MODEL_LIST.md)
- [机器可读清单](manifest.csv)
- [Release 附件映射](RELEASE_ASSETS.md)
- [Release 附件映射 CSV](release_assets.csv)


## 注：大部分模型都有些许瑕疵；例如电音、底噪、气口、呲呲声等。
## 视频中的效果均为经过调音过后的效果。
