---  
title: LightRig
second_title: Aspose.Sildes für .NET API-Referenz  
description: Stellt LightRig dar.
type: docs
weight: 7450  
url: /de/aspose.slides/lightrig/
---  

## LightRig-Klasse  

Stellt LightRig dar.  

```csharp  
public sealed class LightRig : PVIObject, ILightRig  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur-Lese [`IPresentationComponent`](../ipresentationcomponent). |  
| [Direction](../../aspose.slides/lightrig/direction) { get; set; } | Lichtrichtung. Lese/Schreibe [`LightingDirection`](../lightingdirection). |  
| [LightType](../../aspose.slides/lightrig/lighttype) { get; set; } | Stellt einen vordefinierten Lichttyp dar, der auf eine Form angewendet werden kann. Die Lichtanordnung stellt eine Gruppe von Lichtern dar, die auf eine bestimmte Weise relativ zu einer 3D-Szene ausgerichtet sind. Lese/Schreibe [`LightRigPresetType`](../lightrigpresettype). |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |  
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |  
| [GetRotation](../../aspose.slides/lightrig/getrotation)() | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse in Verbindung mit den Breitengrad- und Längengradkoordinaten definiert. Erstes Element im Rückgabearray - Breitengrad, zweites - Längengrad, drittes - Umdrehung. Gibt null zurück, wenn keine Rotation definiert ist. |  
| [SetRotation](../../aspose.slides/lightrig/setrotation)(float, float, float) | Eine Rotation wird durch die Verwendung einer Breitengradkoordinate, einer Längengradkoordinate und einer Umdrehung um die Achse in Verbindung mit den Breitengrad- und Längengradkoordinaten definiert. Wenn einer der Koordinatenwerte float.NaN ist, ist die gesamte Rotation undefiniert. |  

### Siehe auch  

* Klasse [PVIObject](../pviobject)  
* Schnittstelle [ILightRig](../ilightrig)  
* Namensraum [Aspose.Slides](../../aspose.slides)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  