---
title: Fonts
second_title: Référence de l'API Aspose.Slides pour Java
description: Collection de polices.
type: docs
url: /fr/com.aspose.slides/fonts/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Collection de polices.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Renvoie un dictionnaire de toutes les définitions de polices de script dans la présentation. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Obtient le nom de la police associé à une balise de script spécifique à partir du thème de la présentation. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Attribue un nom de police à une balise de script spécifique, ce qui définit la façon dont le texte de ce script sera rendu dans la présentation. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Supprime le réglage de police associé à une balise de script spécifique de la collection de polices du thème. |
| [getLatinFont()](#getLatinFont--) | Renvoie ou définit la police Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Renvoie ou définit la police Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Renvoie ou définit la police Asie de l'Est. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Renvoie ou définit la police Asie de l'Est. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Renvoie ou définit la police de script complexe. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Renvoie ou définit la police de script complexe. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Renvoie un dictionnaire de toutes les définitions de polices de script dans la présentation.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Renvoie:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Un dictionnaire associant des codes de script aux noms de police.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Obtient le nom de la police associé à une balise de script spécifique à partir du thème de la présentation.

--------------------

> ```
> Cet exemple montre comment récupérer la police attribuée au script cyrillique dans le thème de la présentation.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 (p. ex., "Latn", "Cyrl", "Jpan") utilisé pour identifier un système d'écriture. |

**Renvoie :**
java.lang.String - Le nom de la police utilisée pour le script spécifié, ou  null  si le script n'est pas défini.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Attribue un nom de police à une balise de script spécifique, ce qui définit la façon dont le texte de ce script sera rendu dans la présentation.

--------------------

> ```
> Cet exemple montre comment définir la police pour le script arabe à "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 (p. ex., "Arab", "Hebr", "Hans") identifiant le système d'écriture. |
| fontName | java.lang.String | Le nom de la police à attribuer au script spécifié. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Supprime le réglage de police associé à une balise de script spécifique de la collection de polices du thème.

--------------------

> ```
> Cet exemple montre comment supprimer le mappage de police pour le script hébreu :
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 dont le réglage de police doit être supprimé. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Renvoie ou définit la police Latin. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Renvoie ou définit la police Latin. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Renvoie ou définit la police Asie de l'Est. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Renvoie ou définit la police Asie de l'Est. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Renvoie ou définit la police de script complexe. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Renvoie ou définit la police de script complexe. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |