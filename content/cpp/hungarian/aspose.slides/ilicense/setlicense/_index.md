---
title: SetLicense()
second_title: Aspose.Slides for C++ API referencia
description: Licenceli a komponenst.
type: docs
weight: 1
url: /hu/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metódus


Licenceli a komponenst.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Lehet teljes vagy rövid fájlnév vagy beágyazott erőforrás neve. Üres karakterláncot használjon a kiértékelési módra váltáshoz. |
## Megjegyzés



Megpróbálja megtalálni a licencet a következő helyeken:

1. Kifejezett útvonal.

2. A komponens összeállításának mappája.

3. A kliens hívó összeállításának mappája.

4. A belépési összeállítás mappája.

5. Beágyazott erőforrás a kliens hívó összeállításában.

**Megjegyzés:**.NET Compact Framework esetén csak a következő helyeken keres licencet:

1. Kifejezett útvonal.

2. Beágyazott erőforrás a kliens hívó összeállításában.

Ebben a példában megkísérlik megtalálni a MyLicense.lic nevű licencfájlt a komponenst tartalmazó mappában, a hívó összeállítást tartalmazó mappában, a belépési összeállítás mappájában, majd a hívó összeállítás beágyazott erőforrásai között. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metódus


Licenceli a komponenst.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A stream, amely a licencet tartalmazza. |
## Megjegyzés



Használja ezt a metódust licenc betöltéséhez egy stream segítségével.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ILicense](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)