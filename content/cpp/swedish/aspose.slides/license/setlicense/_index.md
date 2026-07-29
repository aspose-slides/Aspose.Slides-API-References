---
title: SetLicense()
second_title: Aspose.Slides för C++ API-referens
description: Licensierar komponenten.
type: docs
weight: 14
url: /sv/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metod


Licensierar komponenten.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Kan vara ett fullt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till evalueringsläge. |
## Anmärkningar



Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen för komponentens assembly.

3. Mappen för klientens anropande assembly.

4. Mappen för start-assemblyn.

5. En inbäddad resurs i klientens anropande assembly.

**Obs:**På .NET Compact Framework försöker den hitta licensen endast på dessa platser:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande assembly.

I detta exempel kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande assemblyn, i mappen för start-assemblyn och sedan i de inbäddade resurserna i den anropande assemblyn. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metod


Licensierar komponenten.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En ström som innehåller licensen. |
## Anmärkningar



Använd den här metoden för att läsa in en licens från en ström.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [License](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)