---
title: SetLicense()
second_title: Aspose.Slides für C++ API-Referenz
description: Lizenziert die Komponente.
type: docs
weight: 14
url: /de/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) Methode


Lizenziert die Komponente.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Kann ein vollständiger oder kurzer Dateiname bzw. der Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln. |
## Bemerkungen



Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner der Komponentenassembly.

3. Der Ordner der aufrufenden Assembly des Clients.

4. Der Ordner der Einstieg-Assembly.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Note:**Auf dem .NET Compact Framework wird versucht, die Lizenz nur an folgenden Orten zu finden:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und danach in den eingebetteten Ressourcen der aufrufenden Assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) Methode


Lizenziert die Komponente.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream, der die Lizenz enthält. |
## Bemerkungen



Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [License](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)