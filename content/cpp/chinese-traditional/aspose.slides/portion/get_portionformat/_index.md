---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個格式化物件，其中包含已明確設定的文字片段的格式屬性，且未套用繼承。唯讀 IPortionFormat.
type: docs
weight: 1
url: /zh-hant/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() 方法


傳回一個格式化物件，該物件包含已明確設定的文字片段的格式屬性，且未套用繼承。唯讀 [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## 備註


格式化物件僅包含針對目前片段定義的格式參數，未套用繼承的資料。

若要取得包括繼承值在內的有效值，請使用 [PortionFormat::GetEffective](../../portionformat/geteffective/) 方法.
## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortionFormat](../../iportionformat/)
* 類別 [Portion](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)