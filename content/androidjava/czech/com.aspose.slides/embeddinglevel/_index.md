---
title: EmbeddingLevel
second_title: Aspose.Slides pro Android pomocí Java API Reference
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
## Pole

| Pole | Popis |
| --- | --- |
| [Installable](#Installable) | Písma s tímto nastavením naznačují, že mohou být vložena a trvale nainstalována na vzdáleném systému aplikací. |
| [Restricted](#Restricted) | Písma, která mají nastaven jen tento bit, nesmí být jakýmkoli způsobem upravována, vkládána nebo vyměňována bez předchozího získání povolení od právního vlastníka. |
| [PreviewPrint](#PreviewPrint) | Když je tento bit nastaven, může být písmo vloženo a dočasně načteno na vzdáleném systému. |
| [Editable](#Editable) | Když je tento bit nastaven, může být písmo vloženo, ale musí být nainstalováno pouze dočasně na jiných systémech. |
| [NoSubsetting](#NoSubsetting) | Když je tento bit nastaven, nesmí být písmo před vložením podmnoženo. |
| [BitmapOnly](#BitmapOnly) | Když je tento bit nastaven, mohou být vloženy pouze bitmapy obsažené v písmu. |
### Instalovatelné {#Installable}
```
public static final int Installable
```

Písma s tímto nastavením naznačují, že mohou být vložena a trvale nainstalována na vzdáleném systému aplikací. Uživatel vzdáleného systému získává stejná práva, povinnosti a licence pro toto písmo jako původní kupující písma a podléhá stejné koncovému licenčnímu ujednání, autorskému právu, designovému patentu a/nebo ochranné známce jako původní kupující.

### Omezené {#Restricted}
```
public static final int Restricted
```

Písma, která mají nastaven jen tento bit, nesmí být jakýmkoli způsobem upravována, vkládána nebo vyměňována bez předchozího získání povolení od právního vlastníka.

### NáhledTisk {#PreviewPrint}
```
public static final int PreviewPrint
```

Když je tento bit nastaven, může být písmo vloženo a dočasně načteno na vzdáleném systému. Dokumenty obsahující Preview & Print písma musí být otevřeny v režimu „pouze ke čtení“; nelze do dokumentu provádět úpravy.

### Upravitelné {#Editable}
```
public static final int Editable
```

Když je tento bit nastaven, může být písmo vloženo, ale musí být nainstalováno pouze dočasně na jiných systémech. Na rozdíl od Preview & Print písem mohou být dokumenty obsahující Editable písma otevřeny ke čtení, úpravy jsou povoleny a změny mohou být uloženy.

### BezPodmnožování {#NoSubsetting}
```
public static final int NoSubsetting
```

Když je tento bit nastaven, nesmí být písmo podmnoženo před vložením. Platí také další omezení vkládání specifikovaná v bitech 0-3 a 9.

### PouzeBitmapy {#BitmapOnly}
```
public static final int BitmapOnly
```

Když je tento bit nastaven, mohou být vloženy pouze bitmapy obsažené v písmu. Žádná obrysová data nemohou být vložena. Pokud v písmu nejsou k dispozici žádné bitmapy, písmo je považováno za nevkládatelné a služby vkládání selžou.