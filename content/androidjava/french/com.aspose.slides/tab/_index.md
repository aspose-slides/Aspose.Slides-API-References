---
title: Tab
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une tabulation pour un texte.
type: docs
url: /fr/com.aspose.slides/tab/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ITab](../../com.aspose.slides/itab)  
```
public final class Tab extends PVIObject implements ITab
```

Représente une tabulation pour un texte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Crée un nouveau Tab |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Renvoie ou définit la position d'une tabulation. |
| [setPosition(double value)](#setPosition-double-) | Renvoie ou définit la position d'une tabulation. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit le style d'alignement d'une tabulation. |
| [setAlignment(int value)](#setAlignment-int-) | Renvoie ou définit le style d'alignement d'une tabulation. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compare l'instance actuelle avec un autre objet du même type. |

### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Crée un nouveau Tab

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | double | Position de la tabulation. |
| align | int | Alignement. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Retour :**
long

### getPosition() {#getPosition--}
```
public final double getPosition()
```

Renvoie ou définit la position d'une tabulation. L'affectation de cette propriété peut modifier l'index de la tabulation dans la collection et invalider l'énumérateur. Lecture/écriture double.

**Retour :**
double

### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Renvoie ou définit la position d'une tabulation. L'affectation de cette propriété peut modifier l'index de la tabulation dans la collection et invalider l'énumérateur. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Renvoie ou définit le style d'alignement d'une tabulation. Lecture/écriture [TabAlignment](../../com.aspose.slides/tabalignment).

**Retour :**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Renvoie ou définit le style d'alignement d'une tabulation. Lecture/écriture [TabAlignment](../../com.aspose.slides/tabalignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Compare l'instance actuelle avec un autre objet du même type.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Un objet à comparer avec cette instance. |

**Retour :**
int - Un entier 32 bits qui indique l'ordre relatif des comparands. La valeur de retour a les significations suivantes :

*  < 0 - Cette instance est inférieure à obj.
*  = 0 - Cette instance est égale à obj.
*  > 0 - Cette instance est supérieure à obj.