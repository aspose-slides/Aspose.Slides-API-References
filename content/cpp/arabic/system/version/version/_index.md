---
title: Version()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مثيلًا يمثل القيم المحددة للإصدار الرئيسي، الفرعي، بناء الإصدار ورقم الإصدار.
type: docs
weight: 1
url: /ar/system/version/version/
---
## Version::Version(int, int, int, int) المُنشئ

ينشئ مثيلًا يمثل القيم المحددة للإصدار الرئيسي، الفرعي، بناء الإصدار والإصدار.

```cpp
System::Version::Version(int major, int minor, int build, int revision)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| major | int | رقم الإصدار الرئيسي |
| minor | int | رقم الإصدار الفرعي |
| build | int | رقم بناء الإصدار |
| revision | int | رقم الإصدار |

## Version::Version(int, int, int) المُنشئ

ينشئ مثيلًا يمثل القيم المحددة للإصدار الرئيسي، الفرعي وبناء الإصدار.

```cpp
System::Version::Version(int major, int minor, int build)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| major | int | رقم الإصدار الرئيسي |
| minor | int | رقم الإصدار الفرعي |
| build | int | رقم بناء الإصدار |

## Version::Version(int, int) المُنشئ

ينشئ مثيلًا يمثل القيم المحددة للإصدار الرئيسي والفرعي.

```cpp
System::Version::Version(int major, int minor)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| major | int | رقم الإصدار الرئيسي |
| minor | int | رقم الإصدار الفرعي |

## Version::Version(const String\&) المُنشئ

ينشئ مثيلًا يمثل رقم الإصدار المُمَثَّل كسلسلة نصية.

```cpp
System::Version::Version(const String &version)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| version | const [String](../../string/)\& | السلسلة النصية التي تحتوي على رقم الإصدار |

## Version::Version() المُنشئ

ينشئ مثيلًا يمثل رقم الإصدار 0.0.-1.-1.

```cpp
System::Version::Version()
```

## انظر أيضًا

* الفئة [Version](../)
* الفئة [String](../../string/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)