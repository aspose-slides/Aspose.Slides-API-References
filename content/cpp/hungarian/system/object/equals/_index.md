---
title: Equals()
second_title: Aspose.Slides for C++ API Referencia
description: Összehasonlítja az objektumokat a C# Object.Equals szemantika szerint.
type: docs
weight: 157
url: /hu/system/object/equals/
---
## Object::Equals(ptr) metódus

Összehasonlítja az objektumokat a C# [Object.Equals](./) szemantika szerint.

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) a jelenlegi objektummal összehasonlítandó. |

### Visszatérési érték

Igaz, ha az objektumok egyenlőnek tekinthetők, egyébként hamis.

## Object::Equals(T1 const\&, T2 const\&) metódus

Referenciatípusú objektumokat hasonlít össze C# stílusban.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlítandó objektum típusa. |
| T2 | A második összehasonlítandó objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | T1 const\& | Az első összehasonlítandó objektum. |
| objB | T2 const\& | A második összehasonlítandó objektum. |

### Visszatérési érték

Igaz, ha az objektumok egyeznek akár referenciával, akár szemantikus módon ([Object.Equals](./)-szerű összehasonlítással), egyébként hamis.

## Object::Equals(T1 const\&, T2 const\&) metódus

Értéktípusú objektumokat hasonlít össze C# stílusban.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlítandó objektum típusa. |
| T2 | A második összehasonlítandó objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | T1 const\& | Az első összehasonlítandó objektum. |
| objB | T2 const\& | A második összehasonlítandó objektum. |

### Visszatérési érték

Igaz, ha az objektumokat az elérhető egyenlőség operátor szerint egyenlőnek tekintik, egyébként hamis.

## Object::Equals(float const\&, float const\&) metódus

C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve magát a NaN-t.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | **float** const\& | Baloldali lebegőpontos érték. |
| objB | **float** const\& | Jobboldali lebegőpontos érték. |

### Visszatérési érték

Igaz, ha **objA** és **objB** egyaránt NaN vagy egyenlő, egyébként hamis.

## Object::Equals(double const\&, double const\&) metódus

C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve magát a NaN-t.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | **double** const\& | Baloldali lebegőpontos érték. |
| objB | **double** const\& | Jobboldali lebegőpontos érték. |

### Visszatérési érték

Igaz, ha **objA** és **objB** egyaránt NaN vagy egyenlő, egyébként hamis.

## Lásd még

* Typedef [ptr](../ptr/)
* Osztály [Object](../)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)