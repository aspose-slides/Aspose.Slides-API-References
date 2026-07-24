---
title: SetLicense()
second_title: Aspose.Slides für C++ API-Referenz
description: Lizenziert die Komponente.
type: docs
weight: 1
url: /de/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) Methode

Lizenziert die Komponente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie einen leeren String, um in den Evaluationsmodus zu wechseln. |

## Hinweise



Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner der Komponenten-Assembly.

3. Der Ordner der aufrufenden Assembly des Clients.

4. Der Ordner der Entry-Assembly.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Hinweis:**Auf dem .NET Compact Framework wird versucht, die Lizenz nur an diesen Orten zu finden:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

In diesem Beispiel wird versucht, eine Lizenzdatei namens MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Entry-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) Methode

Lizenziert die Komponente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream, der die Lizenz enthält. |
## Hinweise



Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ILicense](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)