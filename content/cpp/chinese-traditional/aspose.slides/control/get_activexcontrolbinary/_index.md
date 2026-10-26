---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides C++ API 參考
description: 指定 ActiveX 控制項的持續性，當用於持久化的方法是 PersistStream、PersistStreamInit 或 PersistStorage 時。
type: docs
weight: 118
url: /zh-hant/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() method

指定 ActiveX 控制項的持續性，當用於持久化的方法是 PersistStream、PersistStreamInit 或 PersistStorage 時。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## 備註

以下範例示範如何使用 ActiveXControlBinary 屬性來變更 ActiveX 屬性：
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

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Control](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)