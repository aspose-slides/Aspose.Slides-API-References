---
title: Warning()
second_title: Aspose.Slides for C++ API 參考文件
description: 回呼方法會接收警告並決定是否應該中止操作。
type: docs
weight: 1
url: /zh-hant/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) 方法

回呼方法會接收警告並決定是否應該中止操作。

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | 要處理的警告。 |

### 傳回值

中止決策 [ReturnAction](../../returnaction/)。

## 另請參閱

* 列舉 [ReturnAction](../../returnaction/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IWarningInfo](../../iwarninginfo/)
* 類別 [IWarningCallback](../)
* 命名空間 [Aspose::Slides::Warnings](../../)
* 函式庫 [Aspose.Slides](../../../)