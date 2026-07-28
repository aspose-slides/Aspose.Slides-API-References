---
title: Replace()
second_title: Aspose.Slides C++ API referencia
description: Lecseréli egy érték összes előfordulását egy új értékre egy Span-ben.
type: docs
weight: 287
url: /hu/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) függvény

Lecseréli egy érték összes előfordulását egy új értékre egy [Span](../../system/span/)-ban.

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A span a helyben módosításra |
| oldValue | const T\& | Az érték, amit keresni és cserélni kell |
| newValue | const T\& | Az új érték, amellyel az oldValue-t helyettesíti |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) függvény

Átmásolja az elemeket a source-ból a destination-be, miközben a másolás során a megadott értékeket cseréli.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A source [ReadOnlySpan](../../system/readonlyspan/) a másoláshoz |
| destination | [Span](../../system/span/)\<T\>\& | A destination [Span](../../system/span/) a másoláshoz |
| oldValue | const T\& | Az érték, amit keresni és cserélni kell |
| newValue | const T\& | Az új érték, amellyel az oldValue-t helyettesíti |

## Lásd még

* Osztály [Span](../../system/span/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)