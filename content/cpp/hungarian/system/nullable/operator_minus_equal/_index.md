---
title: operator-=()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy Nullable osztály példányt, amely egy null értéket képvisel.
type: docs
weight: 248
url: /hu/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) metódus


Visszaad egy [Nullable](../) osztály példányt, amely egy null értéket képvisel.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) metódus


Alkalmazza [operator-=()](./)-t a jelenlegi objektum által képviselt értékre, a megadott értéket jobb oldali argumentumként használva.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | A jobboldali értékként használt érték típusa a [operator-=()](./) |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A konstans referencia az értékre, amely a [operator-=()](./) jobboldali argumentumaként szolgál, amelyet a jelenlegi objektum által képviselt értékre alkalmaznak. |

### Visszatérési érték

Az önmagára mutató referencia

## Nullable::operator-=(const Nullable\<T1\>\&) metódus


Alkalmazza [operator-=()](./)-t a jelenlegi objektum által képviselt értékre, a megadott [Nullable](../) objektum által képviselt értéket jobb oldali argumentumként használva.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | A [Nullable](../) objektum alapvető típusa, amelynek értéke a [operator-=()](./) jobboldali argumentumaként használatos. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A konstans referencia a [Nullable](../) objektumra, amelynek értéke a [operator-=()](./) jobboldali argumentumaként szolgál, amit a jelenlegi objektum által képviselt értékre alkalmaznak. |

### Visszatérési érték

Az önmagára mutató referencia

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)