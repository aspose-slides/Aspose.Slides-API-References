---
title: GetDateTimeFormats()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací pole řetězců, kde každý prvek je řetězcová reprezentace aktuálního objektu formátovaná pomocí jednoho ze standardních specifikátorů formátu data a času.
type: docs
weight: 547
url: /cs/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const metoda

Vrací pole řetězců, kde každý prvek je řetězcová reprezentace aktuálního objektu formátovaná pomocí jednoho ze standardních specifikátorů formátu data a času.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const metoda

Vrací pole řetězců, kde každý prvek je řetězcová reprezentace aktuálního objektu formátovaná pomocí zadaného standardního specifikátoru formátu data a času.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | char_t | Standardní specifikátor formátu data a času. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const metoda

Vrací pole řetězců, kde každý prvek je řetězcová reprezentace aktuálního objektu formátovaná pomocí jednoho ze standardních specifikátorů formátu data a času a zadaného poskytovatele formátu.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const metoda

Vrací pole řetězců, kde každý prvek je řetězcová reprezentace aktuálního objektu formátovaná pomocí zadaného standardního specifikátoru formátu data a času a poskytovatele formátu.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | char_t | Standardní specifikátor formátu data a času. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [DateTime](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)