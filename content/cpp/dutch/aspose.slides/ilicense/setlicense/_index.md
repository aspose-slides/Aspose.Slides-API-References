---
title: SetLicense()
second_title: Aspose.Slides voor C++ API-referentie
description: Licentieert de component.
type: docs
weight: 1
url: /nl/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) methode

Licentieert de component.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege tekenreeks om naar evaluatiemodus te schakelen. |
## Opmerkingen

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.
2. De map van de componentassembly.
3. De map van de aanroepende assembly van de client.
4. De map van de entry-assembly.
5. Een ingebedde resource in de aanroepende assembly van de client.

**Opmerking:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.
2. Een ingebedde resource in de aanroepende assembly van de client.

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die de component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) methode

Licentieert de component.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een stream die de licentie bevat. |
## Opmerkingen

Gebruik deze methode om een licentie te laden vanuit een stream.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ILicense](../)
* Klasse [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)