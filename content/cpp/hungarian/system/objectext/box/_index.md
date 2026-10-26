---
title: Box()
second_title: Aspose.Slides for C++ API Referencia
description: Értéktípusokat csomagol a(z) Object típusra konvertáláshoz. Implementáció enum típusokhoz.
type: docs
weight: 40
url: /hu/system/objectext/box/
---
## ObjectExt::Box(const T\&) metódus


Értéktípusokat csomagol a(z) [Object](../../object/)-ba konvertáláshoz. Implementáció enum típusokhoz.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) érték csomagoláshoz. |

### Visszatérési érték

Okos mutató az értéket tároló objektumra.

## ObjectExt::Box(const T\&) metódus


Értéktípusokat csomagol a(z) [Object](../../object/)-ba konvertáláshoz. Implementáció nem enum típusokhoz.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | Értéktípus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Csomagolni kívánt érték. |

### Visszatérési érték

Okos mutató az értéket tároló objektumra.

## ObjectExt::Box(const T\&) metódus


[Nullable](../../nullable/) típusokat csomagol a(z) [Object](../../object/)-ba konvertáláshoz.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | Értéktípus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Csomagolni kívánt érték. |

### Visszatérési érték

Okos mutató az értéket tároló objektumra.

## ObjectExt::Box(const String\&) metódus


String értékeket csomagol.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Csomagolni kívánt érték. |

### Visszatérési érték

Csomagolt érték vagy null, ha a forrás string null.

## Lásd még

* Osztály [SmartPtr](../../smartptr/)
* Osztály [Object](../../object/)
* Osztály [ObjectExt](../)
* Osztály [String](../../string/)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)