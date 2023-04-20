---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of the BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /cpp/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() constructor


Constructs a new instance of the [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) constructor


Constructs a new instance of the [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Smart pointer to the stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Wrapping mode |
| locale | const std::locale\& | [Stream](../../stream/)'s locale |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) constructor


Copy constructor. Deleted.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) constructor


Move constructor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) to be move |

## See Also

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BasicSystemIOStreamBuf](../)
* Class [Stream](../../stream/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)