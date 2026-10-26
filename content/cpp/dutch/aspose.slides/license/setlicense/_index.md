---
title: SetLicense()
second_title: Aspose.Slides voor C++ API-referentie
description: Licentieert de component.
type: docs
weight: 14
url: /nl/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) methode


Licentieert de component.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege tekenreeks om over te schakelen naar evaluatiemodus. |
## Opmerkingen



Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map van de componentassemblage.

3. De map van de oproepende assembly van de client.

4. De map van de entry-assembly.

5. Een ingebedde resource in de oproepende assembly van de client.

**Opmerking:**Op het .NET Compact Framework wordt geprobeerd de licentie alleen op deze locaties te vinden:

1. Expliciet pad.

2. Een ingebedde resource in de oproepende assembly van de client.

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die de component bevat, in de map die de oproepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de oproepende assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) methode


Licentieert de component.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

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
* Klasse [License](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)