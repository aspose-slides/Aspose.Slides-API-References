---
title: SendWarning()
second_title: Aspose.Slides for C++ API 參考
description: 如果 receiver 不為 null，則向指定的 receiver 結束警告，並在 receiver 決定中止操作時拋出 AbortRequestedException。
type: docs
weight: 27
url: /zh-hant/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) 方法

如果 receiver 不為 null，則向指定的 receiver 結束警告，並在 receiver 決定中止操作時拋出 AbortRequestedException。

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | 接收器物件 [IWarningCallback](../../iwarningcallback/) |

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IWarningCallback](../../iwarningcallback/)
* 類別 [IWarningInfo](../)
* 命名空間 [Aspose::Slides::Warnings](../../)
* 函式庫 [Aspose.Slides](../../../)