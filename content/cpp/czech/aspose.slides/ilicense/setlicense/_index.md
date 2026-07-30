---
title: SetLicense()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Licencuje komponentu.
type: docs
weight: 1
url: /cs/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metoda


Licencuje komponentu.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Může být úplný nebo zkrácený název souboru nebo název vloženého zdroje. Použijte prázdný řetězec k přepnutí do evaluačního režimu. |
## Poznámky



Zkouší najít licenci v následujících umístěních:

1. Explicitní cesta.
2. Složka sestavení komponenty.
3. Složka volajícího sestavení klienta.
4. Složka vstupního sestavení.
5. Vložený zdroj v volajícím sestavení klienta.

**Poznámka:**Na .NET Compact Framework se licence hledá pouze v těchto umístěních:

1. Explicitní cesta.
2. Vložený zdroj v volajícím sestavení klienta.

V tomto příkladu bude provedeno pokus najít licenční soubor s názvem MyLicense.lic ve složce obsahující komponentu, ve složce obsahující volající sestavení, ve složce vstupního sestavení a poté ve vložených zdrojích volajícího sestavení. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metoda


Licencuje komponentu.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Datový proud, který obsahuje licenci. |
## Poznámky



Použijte tuto metodu k načtení licence ze streamu.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ILicense](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)