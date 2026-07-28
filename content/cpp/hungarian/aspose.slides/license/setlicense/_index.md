---
title: SetLicense()
second_title: Aspose.Slides C++ API Referencia
description: Licenceli a komponenst.
type: docs
weight: 14
url: /hu/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metódus


Licenceli a komponenst.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Lehet teljes vagy rövid fájlnév, vagy beágyazott erőforrás neve. Üres karakterlánc használatával átvált értékelési módra. |
## Remarks



Megpróbálja megtalálni a licencet a következő helyeken:

1. Kifejezett útvonal.

2. A komponens összeszerelés mappája.

3. Az ügyfél hívó összeszerelésének mappája.

4. A belépő összeszerelés mappája.

5. Beágyazott erőforrás az ügyfél hívó összeszerelésében.

**Megjegyzés:**.NET Compact Framework esetén a licencet csak az alábbi helyeken keresi:

1. Kifejezett útvonal.

2. Beágyazott erőforrás az ügyfél hívó összeszerelésében.

Ebben a példában megkísérlik megtalálni a MyLicense.lic nevű licencfájlt a komponenst tartalmazó mappában, a hívó összeszerelést tartalmazó mappában, a belépő összeszerelés mappájában, majd a hívó összeszerelés beágyazott erőforrásai között. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metódus


Licenceli a komponenst.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, amely a licencet tartalmazza. |
## Remarks



Ezzel a metódussal licencet tölthet be egy adatfolyamból.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [License](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)