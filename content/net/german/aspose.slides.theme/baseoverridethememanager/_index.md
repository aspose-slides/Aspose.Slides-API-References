---  
title: BaseOverrideThemeManager
second_title: Aspose.Sildes für .NET API Referenz  
description: Basisklasse für Klassen, die Zugang zu verschiedenen Arten von überschriebenen Themen bieten.
type: docs
weight: 10730  
url: /de/aspose.slides.theme/baseoverridethememanager/
---  

## BaseOverrideThemeManager-Klasse  

Basisklasse für Klassen, die Zugang zu verschiedenen Arten von überschriebenen Themen bieten.  

```csharp  
public abstract class BaseOverrideThemeManager : BaseThemeManager, IOverrideThemeManager  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [IsOverrideThemeEnabled](../../aspose.slides.theme/baseoverridethememanager/isoverridethemeenabled) { get; } | Bestimmt, ob das OverrideTheme das geerbte effektive Thema überschreibt oder nicht. Um das OverrideTheme zum Überschreiben zu aktivieren, verwenden Sie die Methoden OverrideTheme.Init*(). Um das OverrideTheme vom Überschreiben abzuhalten, verwenden Sie die Methode OverrideTheme.Clear(). Nur lesbarer Boolescher Wert. |  
| [OverrideTheme](../../aspose.slides.theme/baseoverridethememanager/overridetheme) { get; set; } | Gibt das überschreibende Themenobjekt zurück. Lese-/Schreibzugriff [`IOverrideTheme`](../ioverridetheme). |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [ApplyColorScheme](../../aspose.slides.theme/baseoverridethememanager/applycolorscheme)(IExtraColorScheme) | Wendet ein zusätzliches Farbschema auf eine Folie an. |  
| [CreateThemeEffective](../../aspose.slides.theme/baseoverridethememanager/createthemeeffective)() | Gibt das Themenobjekt zurück. |  

### Siehe auch  

* Klasse [BaseThemeManager](../basethememanager)  
* Schnittstelle [IOverrideThemeManager](../ioverridethememanager)  
* Namespace [Aspose.Slides.Theme](../../aspose.slides.theme)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  