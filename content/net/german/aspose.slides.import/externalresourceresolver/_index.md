---
title: ExternalResourceResolver
second_title: Aspose.Slides für .NET API-Referenz
description: Callback-Klasse, die verwendet wird, um externe Ressourcen während des Imports von Html Svg-Dokumenten aufzulösen. Die Verwendung dieses Resolvers könnte eine Sicherheitsanfälligkeit schaffen, wenn eine vom Client bereitgestellte HTML- oder SVG-Datei dazu führt, dass die Server-Software lokale oder Netzwerkdateien abruft. Mit Vorsicht verwenden. Es wird empfohlen, ExternalResourceResolver überhaupt nicht anzugeben nur eingebettete Objekte werden gelesen oder eine Unterklasse zu erstellen, die überprüft, ob die angegebene URI gültig ist.
type: docs
weight: 7250
url: /de/aspose.slides.import/externalresourceresolver/
---

## ExternalResourceResolver-Klasse

Callback-Klasse, die verwendet wird, um externe Ressourcen während des Imports von Html, Svg-Dokumenten aufzulösen. Die Verwendung dieses Resolvers könnte eine Sicherheitsanfälligkeit schaffen, wenn eine vom Client bereitgestellte HTML- oder SVG-Datei dazu führt, dass die Server-Software lokale oder Netzwerkdateien abruft. Mit Vorsicht verwenden. Es wird empfohlen, ExternalResourceResolver überhaupt nicht anzugeben (nur eingebettete Objekte werden gelesen) oder eine Unterklasse zu erstellen, die überprüft, ob die angegebene URI gültig ist.

```csharp
public class ExternalResourceResolver : IExternalResourceResolver
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ExternalResourceResolver](externalresourceresolver)() | Der Standard-Konstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetEntity](../../aspose.slides.import/externalresourceresolver/getentity)(string) | Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält. |
| virtual [ResolveUri](../../aspose.slides.import/externalresourceresolver/resolveuri)(string, string) | Löst die absolute URI aus der Basis- und relativen URIs auf. |

### Siehe auch

* interface [IExternalResourceResolver](../iexternalresourceresolver)
* namespace [Aspose.Slides.Import](../../aspose.slides.import)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->