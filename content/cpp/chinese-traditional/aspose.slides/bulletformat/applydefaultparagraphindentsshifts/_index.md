---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides for C++ API 參考文件
description: "當啟用項目符號時，為有效的段落 Indent 和 MarginLeft 設定預設的非零位移（如 PowerPoint 在啟用段落項目符號/編號時的行為）。如果停用項目符號，則僅重設段落 Indent 和 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的行為）。位移的套用會依據目前的項目符號情境 — IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及第一段的 FontHeight 來決定。非零的位移會套用到當前段落的有效 Indent 和 MarginLeft（使結果值為局部值）。"
type: docs
weight: 235
url: /zh-hant/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() 方法

當啟用項目符號時，為有效的段落 Indent 和 MarginLeft 設定預設的非零位移（如 PowerPoint 在啟用段落項目符號/編號時的行為）。如果停用項目符號，則僅重設段落 Indent 和 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的行為）。位移的應用會根據目前的項目符號環境——IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及第一段的 FontHeight 來決定。非零的位移會套用到目前段落的有效 Indent 和 MarginLeft（使結果值為局部值）。

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```

## 參見

* 類別 [BulletFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)