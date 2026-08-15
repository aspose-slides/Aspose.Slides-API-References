---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides for C++ API 參考
description: 建立 BasicSystemIStreamWrapper 的新實例。
type: docs
weight: 1
url: /zh-hant/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor


建立 [BasicSystemIStreamWrapper](../) 的新實例。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 指向串流的指標 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 封裝模式 |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) constructor


拷貝建構函式。已刪除。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) constructor


移動建構函式。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) 要搬移 |

## 另請參閱

* 列舉 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../stream/)
* 類別 [BasicSystemIStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)