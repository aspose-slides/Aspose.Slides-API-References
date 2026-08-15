---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides C++ API 參考文件
description: "在啟用項目符號時，設定有效段落 Indent 和 MarginLeft 的預設非零位移（如 PowerPoint 在啟用段落項目符號/編號時的做法）。若項目符號被停用，則僅重設段落 Indent 和 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的做法）。位移會根據當前項目符號上下文套用——IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及第一段的 FontHeight。非零位移會套用到當前段落的有效 Indent 和 MarginLeft（使結果值成為區域值）。"
type: docs
weight: 235
url: /zh-hant/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() 方法


當啟用項目符號時，設定有效段落 Indent 和 MarginLeft 的預設非零位移（如 PowerPoint 在啟用段落項目符號/編號時的做法）。若項目符號被停用，則僅重設段落 Indent 和 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的做法）。位移會根據當前項目符號上下文套用——IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及第一段落的 FontHeight。非零位移會套用至當前段落的有效 Indent 和 MarginLeft（使結果值成為區域值）。

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```


## 相關參考

* 類別 [IBulletFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)