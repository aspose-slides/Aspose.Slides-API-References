---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API 參考
description: 傳回格式化物件，其中包含已明確設定的文字區段之格式屬性，且未套用繼承。唯讀 IPortionFormat.
type: docs
weight: 1
url: /zh-hant/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() 方法


傳回格式化物件，其中包含已明確設定的文字區段之格式屬性，且未套用繼承。唯讀 [IPortionFormat](../../iportionformat/)。

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## 備註


此格式化物件僅包含針對目前區段定義的格式參數，未套用繼承的資料。

若要取得包含繼承值的實際值，請使用 [IPortionFormat::GetEffective](../../iportionformat/geteffective/) 方法。
## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortionFormat](../../iportionformat/)
* Class [IPortion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)