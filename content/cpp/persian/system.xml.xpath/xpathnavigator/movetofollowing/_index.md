---
title: MoveToFollowing()
second_title: Aspose.Slides برای C++ مرجع API
description: XPathNavigator را به عنصری که نام محلی و URI فضای نام آن در ترتیب سند مشخص شده است، منتقل می‌کند.
type: docs
weight: 703
url: /fa/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) متد

[XPathNavigator](../) را به عنصری که نام محلی و URI فضای نام آن در ترتیب سند مشخص شده است، منتقل می‌کند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی عنصر. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصر. |

### Return Value

**true** اگر [XPathNavigator](../) به‌طور موفقیت‌آمیز جابه‌جا شد؛ در غیر این صورت **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) متد

[XPathNavigator](../) را به عنصری که نام محلی و URI فضای نام آن مشخص شده است، تا مرز مشخص‌شده، در ترتیب سند، منتقل می‌کند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی عنصر. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصر. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | شیء [XPathNavigator](../) که بر روی مرز عنصر قرار دارد و [XPathNavigator](../) جاری هنگام جستجو برای عنصر بعدی از عبور از آن جلوگیری می‌کند. |

### Return Value

**true** اگر [XPathNavigator](../) به‌طور موفقیت‌آمیز جابه‌جا شد؛ در غیر این صورت **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) متد

[XPathNavigator](../) را به عنصر بعدی از نوع XPathNodeType مشخص‌شده، در ترتیب سند، منتقل می‌کند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType عنصر. XPathNodeType نمی‌تواند [XPathNodeType::Attribute](../../xpathnodetype/) یا [XPathNodeType::Namespace](../../xpathnodetype/) باشد. |

### Return Value

**true** اگر [XPathNavigator](../) به‌طور موفقیت‌آمیز جابه‌جا شد؛ در غیر این صورت **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) متد

[XPathNavigator](../) را به عنصر بعدی از نوع XPathNodeType مشخص‌شده، تا مرز مشخص‌شده، در ترتیب سند، منتقل می‌کند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType عنصر. XPathNodeType نمی‌تواند [XPathNodeType::Attribute](../../xpathnodetype/) یا [XPathNodeType::Namespace](../../xpathnodetype/) باشد. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | شیء [XPathNavigator](../) که بر روی مرز عنصر قرار دارد و [XPathNavigator](../) جاری هنگام جستجو برای عنصر بعدی از عبور از آن جلوگیری می‌کند. |

### Return Value

**true** اگر [XPathNavigator](../) به‌طور موفقیت‌آمیز جابه‌جا شد؛ در غیر این صورت **false**.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)