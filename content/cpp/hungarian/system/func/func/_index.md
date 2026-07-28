---
title: Func()
second_title: Aspose.Slides for C++ API hivatkozás
description: Alapértelmezett konstruktor, amely null-Func-ot hoz létre.
type: docs
weight: 1
url: /hu/system/func/func/
---
## Func::Func() konstruktor


Alapértelmezett konstruktor, amely null-Func-ot hoz létre.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) konstruktor


Konstruktor, amely létrehozza a [Func](../) objektumot, és értéket (valódi visszahívás vagy nullptr) rendel hozzá.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | Argumentum típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T\&& | Argumentum. |

## Func::Func(const Func\&) konstruktor


Másoló konstruktor.

```cpp
System::Func<Args>::Func(const Func &func)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) amiből az adatokat másolni kell. |

## Func::Func(Func\&&) konstruktor


Mozgató konstruktor.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) amiből az adatokat mozgatni kell. |

## Lásd még

* Osztály [Func](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)