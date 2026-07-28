---
title: LoadingStreamBehavior
second_title: Aspose.Slides dla C++ API Reference
description: "Obiekt System::IO::Stream przekazywany do metody jest traktowany jako Binary Large Object (BLOB) (zobacz opis IBlobManagementOptions). Wartości tego wyliczenia określają, jak System::IO::Stream powinien być traktowany, gdy zostanie przekazany do metody. W zależności od wymagań można podjąć różne decyzje, aby zapewnić najbardziej efektywne zachowanie."
type: docs
weight: 6735
url: /pl/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

Obiekt [System::IO::Stream](../../system.io/stream/) przekazywany do metody jest traktowany jako Binary Large Object (BLOB) (zobacz opis [IBlobManagementOptions](../iblobmanagementoptions/)). Wartości tego wyliczenia określają, jak [System::IO::Stream](../../system.io/stream/) powinien być traktowany, gdy zostanie przekazany do metody. W zależności od wymagań można podjąć różne decyzje, aby zapewnić najbardziej efektywne zachowanie.

```cpp
enum class LoadingStreamBehavior
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Strumień zostanie odczytany do końca i następnie zwolniony - tzn. będzie zagwarantowane, że ten strumień nie będzie używany przez instancję [IPresentation](../ipresentation/) w przyszłości. Może być zamknięty przez kod klienta lub wykorzystany w inny sposób. |
| KeepLocked | 1 | Strumień zostanie zablokowany wewnątrz obiektu [IPresentation](../ipresentation/), tzn. własność strumienia zostanie przekazana. Obiekt [IPresentation](../ipresentation/) będzie odpowiedzialny za prawidłowe zwolnienie strumienia, gdy ten obiekt zostanie sam zwolniony. To zachowanie jest niezwykle przydatne, gdy trzeba serializować duży plik BLOB (np. duży plik wideo lub audio - zobacz opis [IBlobManagementOptions](../iblobmanagementoptions/)) i chce się uniknąć ładowania tego pliku do pamięci lub innych problemów wydajnościowych. Można po prostu otworzyć [System::IO::FileStream](../../system.io/filestream/) dla tego pliku i przekazać go do metody, wybierając [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)