---
title: StringWriter()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy új StringWriter példányt a megadott StringBuilder és IFormatProvider használatával.
type: docs
weight: 1
url: /hu/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) konstruktor


Létrehoz egy új példányt a [StringWriter](../)-ből a megadott StringBuilder és [IFormatProvider](../../../system/iformatprovider/) használatával.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | A StringBuilder objektum, amelyet a létrehozott [StringWriter](../) használ |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Egy [IFormatProvider](../../../system/iformatprovider/) objektum, amelyet a létrehozott objektum használ |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) konstruktor


Létrehoz egy új példányt a [StringWriter](../)-ből a megadott StringBuilder és a jelenlegi kultúrából származó [IFormatProvider](../../../system/iformatprovider/) használatával.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | A StringBuilder objektum, amelyet a létrehozott [StringWriter](../) használ |

## StringWriter::StringWriter(const IFormatProviderPtr\&) konstruktor


Létrehoz egy új példányt a [StringWriter](../)-ből a megadott [IFormatProvider](../../../system/iformatprovider/) használatával.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Egy [IFormatProvider](../../../system/iformatprovider/) objektum, amelyet a létrehozott objektum használ |

## StringWriter::StringWriter() konstruktor


Létrehoz egy új példányt a [StringWriter](../)-ből a jelenlegi kultúrából származó [IFormatProvider](../../../system/iformatprovider/) használatával.

```cpp
System::IO::StringWriter::StringWriter()
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Osztály [StringBuilder](../../../system.text/stringbuilder/)
* Osztály [StringWriter](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)