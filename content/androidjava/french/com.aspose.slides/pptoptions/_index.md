---
title: PptOptions
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PPT.
type: docs
url: /fr/com.aspose.slides/pptoptions/
---
**Héritage :**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable  
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PPT.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Représente le GUID de la classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Représente le GUID de la classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. |

### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

Représente le GUID de la classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// set CLSID to 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
> public final void setRootDirectoryClsid(UUID value)
> 
> Représente le GUID de la classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// set CLSID to 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |