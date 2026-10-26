---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides for C++ API 參考
description: 建立 BasicSystemOStreamWrapper 的新實例。
type: docs
weight: 1
url: /zh-hant/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 建構函式

建立 [BasicSystemOStreamWrapper](../) 的新實例。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 指向串流的指標 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 封裝模式 |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) 建構函式

複製建構函式。已刪除。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) 建構函式

移動建構函式。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) 將被移動 |

## 另見

* 列舉 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../stream/)
* 類別 [BasicSystemOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)