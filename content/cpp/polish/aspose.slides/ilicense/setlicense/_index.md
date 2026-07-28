---
title: SetLicense()
second_title: Aspose.Slides dla C++ odniesienie API
description: Licencjonuje komponent.
type: docs
weight: 1
url: /pl/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metoda

Licencjonuje komponent.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Może być pełną lub krótką nazwą pliku lub nazwą zasobu osadzonego. Użyj pustego ciągu, aby przełączyć w tryb ewaluacji. |

## Uwagi

Próbuje znaleźć licencję w następujących lokalizacjach:

1. Ścieżka jawna.
2. Folder zestawu komponentu.
3. Folder zestawu wywołującego klienta.
4. Folder zestawu wejściowego.
5. Osadzony zasób w zestawie wywołującego klienta.

**Uwaga:**W .NET Compact Framework, próbuje znaleźć licencję tylko w tych lokalizacjach:

1. Ścieżka jawna.
2. Osadzony zasób w zestawie wywołującego klienta.

W tym przykładzie zostanie podjęta próba znalezienia pliku licencyjnego o nazwie MyLicense.lic w folderze zawierającym komponent, w folderze zawierającym wywołujący zestaw, w folderze zestawu wejściowego, a następnie w osadzonych zasobach wywołującego zestawu. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metoda

Licencjonuje komponent.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień zawierający licencję. |

## Uwagi

Użyj tej metody, aby wczytać licencję ze strumienia.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ILicense](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)