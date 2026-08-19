---
title: EmbeddingLevel
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Zastupuje licenční práva pro vložení písma.
type: docs
url: /cs/com.aspose.slides/embeddinglevel/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Zastupuje licenční práva pro vložení písma.
## Pola

| Pole | Popis |
| --- | --- |
| [Installable](#Installable) | Písma s tímto nastavením indikují, že mohou být vložena a trvale nainstalována na vzdáleném systému aplikací. |
| [Restricted](#Restricted) | Písma, u nichž je nastaven pouze tento bit, nesmí být upravována, vkládána ani vyměňována žádným způsobem bez předchozího získání povolení od právního vlastníka. |
| [PreviewPrint](#PreviewPrint) | Když je tento bit nastaven, písmo může být vloženo a dočasně načteno na vzdáleném systému. |
| [Editable](#Editable) | Když je tento bit nastaven, písmo může být vloženo, ale musí být nainstalováno pouze dočasně na jiných systémech. |
| [NoSubsetting](#NoSubsetting) | Když je tento bit nastaven, písmo nesmí být před vložením podrobeno podskupině. |
| [BitmapOnly](#BitmapOnly) | Když je tento bit nastaven, mohou být vloženy pouze bitmapy obsažené v písmu. |
### Instalovatelný {#Installable}
```
public static final int Installable
```

Písma s tímto nastavením indikují, že mohou být vložena a trvale nainstalována na vzdáleném systému aplikací. Uživatel vzdáleného systému získává stejné práva, povinnosti a licence pro toto písmo jako původní kupující písma a podléhá stejné koncovému licenčnímu ujednání, autorskému právu, designovému patentu a/nebo ochranné známce jako původní kupující.

### Omezený {#Restricted}
```
public static final int Restricted
```

Písma, u nichž je nastaven pouze tento bit, nesmí být upravována, vkládána ani vyměňována žádným způsobem bez předchozího získání povolení od právního vlastníka.

### Náhled a tisk {#PreviewPrint}
```
public static final int PreviewPrint
```

Když je tento bit nastaven, písmo může být vloženo a dočasně načteno na vzdáleném systému. Dokumenty obsahující písma pro náhled a tisk musí být otevřeny jen pro čtení; nelze v nich provádět úpravy.

### Upravitelné {#Editable}
```
public static final int Editable
```

Když je tento bit nastaven, písmo může být vloženo, ale musí být nainstalováno pouze dočasně na jiných systémech. Na rozdíl od písem pro náhled a tisk mohou být dokumenty obsahující upravitelná písma otevřeny pro čtení, úpravy jsou povoleny a změny mohou být uloženy.

### Bez podskupin {#NoSubsetting}
```
public static final int NoSubsetting
```

Když je tento bit nastaven, písmo nesmí být před vložením podrobeno podskupině. Platí také další omezení vložení uvedená v bitech 0-3 a 9.

### Pouze bitmapy {#BitmapOnly}
```
public static final int BitmapOnly
```

Když je tento bit nastazen, mohou být vloženy jen bitmapy obsažené v písmu. Žádná obrysová data nemohou být vložena. Pokud v písmu nejsou k dispozici žádné bitmapy, písmo se považuje za nevložitelný a služby vložení selžou.