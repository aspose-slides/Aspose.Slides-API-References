---
title: SetLicense()
second_title: Aspose.Slides för C++ API-referens
description: Licensierar komponenten.
type: docs
weight: 1
url: /sv/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metod

Licensierar komponenten.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |

## Anmärkningar

Försöker hitta licensen på följande platser:

1. Explicit sökväg.
2. Mappen för komponentens assembly.
3. Mappen för klientens anropande assembly.
4. Mappen för startassemblyn.
5. En inbäddad resurs i klientens anropande assembly.

**Note:**På .NET Compact Framework försöker den endast hitta licensen på följande platser:

1. Explicit sökväg.
2. En inbäddad resurs i klientens anropande assembly.

I detta exempel kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande assemblyn, i startassemblyns mapp och sedan i de inbäddade resurserna i den anropande assemblyn. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metod

Licensierar komponenten.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En ström som innehåller licensen. |

## Anmärkningar

Använd denna metod för att läsa in en licens från en ström.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [ILicense](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)