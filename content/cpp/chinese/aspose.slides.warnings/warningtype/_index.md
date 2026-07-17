---
title: WarningType
second_title: Aspose.Slides C++ API 参考
description: 表示一种警告类型。
type: docs
weight: 92
url: /zh/aspose.slides.warnings/warningtype/
---
## WarningType 枚举

表示一种警告类型。

```cpp
enum class WarningType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| SourceFileCorruption | 0 | 已在源文档中检测到问题，极有可能在以原始格式保存后无法打开文档。 |
| DataLoss | 1 | 文本/图表/图像或其他数据将在加载后的文档树或保存后的文档中完全缺失。 |
| MajorFormattingLoss | 2 | 重大格式丢失。 |
| MinorFormattingLoss | 3 | 次要格式丢失。 |
| CompatibilityIssue | 4 | 已知问题会阻止某些用户代理或旧版本用户代理打开文档。 |
| UnexpectedContent | 99 | 源文档中的某些内容无法识别（即不受支持），这可能会导致问题或造成数据/格式丢失。 |

## 另请参阅

* 命名空间 [Aspose::Slides::Warnings](../)
* 库 [Aspose.Slides](../../)