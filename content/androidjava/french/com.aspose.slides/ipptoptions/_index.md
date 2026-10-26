---
title: IPptOptions
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PPT.
type: docs
url: /fr/com.aspose.slides/ipptoptions/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PPT.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
``` 
public abstract UUID getRootDirectoryClsid()
```

Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'.

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
public abstract void setRootDirectoryClsid(UUID value)

Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |