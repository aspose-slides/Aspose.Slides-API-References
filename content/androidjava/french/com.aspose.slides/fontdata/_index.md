---
title: FontData
second_title: Référence API Java pour Aspose.Slides pour Android
description: Représente une définition de police.
type: docs
url: /fr/com.aspose.slides/fontdata/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)  
```
public final class FontData implements IFontData
```

Représente une définition de police. Immuable.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Crée un nouvel objet FontData avec le nom de police spécifié. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Renvoie le nom de la police. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Renvoie le nom de la police, en remplaçant la référence du thème par une police réellement utilisée. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si deux instances de FontData sont égales. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
| [toString()](#toString--) | Renvoie la représentation sous forme de chaîne. |

### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Crée un nouvel objet FontData avec le nom de police spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Renvoie le nom de la police. Lecture/écriture String.

**Renvoie :**
java.lang.String

### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Renvoie le nom de la police, en remplaçant la référence du thème par une police réellement utilisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thème à partir duquel le nom de police thématisé doit être pris. Il appartient à l'appelant de fournir une valeur correcte. Voir [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Renvoie :**
java.lang.String - Nom de la police.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si deux instances de FontData sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le FontData à comparer avec le FontData actuel. |

**Renvoie :**
boolean - **true** si le FontData spécifié est égal au FontData actuel ; sinon, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sert de fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.

**Renvoie :**
int - Code de hachage du FontData.

### toString() {#toString--}
```
public String toString()
```

Renvoie la représentation sous forme de chaîne.

**Renvoie :**
java.lang.String - Représentation sous forme de chaîne.