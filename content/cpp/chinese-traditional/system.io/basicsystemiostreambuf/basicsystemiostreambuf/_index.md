---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides for C++ API 參考
description: 建立 BasicSystemIOStreamBuf 的新實例。
type: docs
weight: 14
url: /zh-hant/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() 建構子

建立新的 [BasicSystemIOStreamBuf](../) 實例。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) 建構子

建立新的 [BasicSystemIOStreamBuf](../) 實例。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 指向串流的智慧指標 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 包裝模式 |
| locale | const std::locale\& | [Stream](../../stream/) 的區域設定 |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) 建構子

拷貝建構子。已刪除。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) 建構子

移動建構子。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) 要被移動 |

## 另請參閱

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [BasicSystemIOStreamBuf](../)
* 類別 [Stream](../../stream/)
* 名稱空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)