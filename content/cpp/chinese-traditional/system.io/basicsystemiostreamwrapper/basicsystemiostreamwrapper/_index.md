---
title: BasicSystemIOStreamWrapper()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立 BasicSystemIOStreamWrapper 的新實例。
type: docs
weight: 1
url: /zh-hant/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 建構函式


建立 [BasicSystemIOStreamWrapper](../) 的新實例。

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 指向串流的指標 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 包裝模式 |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) 建構函式


複製建構函式。已刪除。

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) 建構函式


移動建構函式。

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) 以移動 |

## 另請參閱

* 列舉 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../stream/)
* 類別 [BasicSystemIOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)