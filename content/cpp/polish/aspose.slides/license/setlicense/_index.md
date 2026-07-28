---
title: SetLicense()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Licencjonuje komponent.
type: docs
weight: 14
url: /pl/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metoda


Licencjonuje komponent.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Może być pełną lub skróconą nazwą pliku lub nazwą zasobu osadzonego. Użyj pustego łańcucha, aby przełączyć się w tryb ewaluacji. |
## Uwagi



Próbuje znaleźć licencję w następujących lokalizacjach:

1. Ścieżka jawna.

2. Folder zestawu komponentu.

3. Folder wywołującego zestawu klienta.

4. Folder zestawu wejściowego.

5. Zasób osadzony w wywołującym zestawie klienta.

**Uwaga:**W .NET Compact Framework próbuje znaleźć licencję tylko w tych lokalizacjach:

1. Ścieżka jawna.

2. Zasób osadzony w wywołującym zestawie klienta.

W tym przykładzie zostanie podjęta próba znalezienia pliku licencji o nazwie MyLicense.lic w folderze zawierającym komponent, w folderze zawierającym wywołujący zestaw, w folderze zestawu wejściowego, a następnie w zasobach osadzonych wywołującego zestawu. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metoda


Licencjonuje komponent.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień zawierający licencję. |
## Uwagi



Użyj tej metody, aby załadować licencję ze strumienia.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [License](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)