---
title: get_Persistence()
second_title: Aspose.Slides C++ API 參考
description: 取得用於儲存 ActiveX 控制項屬性的方式。只讀 PersistenceType.
type: docs
weight: 1
url: /zh-hant/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() 方法


取得用於儲存 ActiveX 控制項屬性的方式。只讀 [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## 備註


以下範例示範使用 Persistence 屬性，以檢查 ActiveX 物件的屬性是否可以作為基於 XML 的 ActiveX 屬性進行變更： 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // 使用您自己的方法來管理儲存在其二進位檔案中的 ActiveX 屬性
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## 另見

* Enum [PersistenceType](../../persistencetype/)
* 類別 [Control](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)