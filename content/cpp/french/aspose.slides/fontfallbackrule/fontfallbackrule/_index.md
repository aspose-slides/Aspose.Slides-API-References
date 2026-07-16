---
title: FontFallBackRule()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle instance.
type: docs
weight: 66
url: /fr/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) constructeur

Crée une nouvelle instance.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **uint32_t** | Indice de début de la plage unicode |
| endIndex | **uint32_t** | Indice de fin de la plage unicode |
| fontNames | [System::String](../../../system/string/) | Nom(s) de police (séparés par des virgules) pour le FallBack |
## Remarques

```cpp
// Créer une nouvelle instance de FontFallBackRule avec une police.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Créer une nouvelle instance de FontFallBackRule avec plusieurs polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) constructeur

Crée une nouvelle instance.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **uint32_t** | Indice de début de la plage unicode |
| endIndex | **uint32_t** | Indice de fin de la plage unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nom(s) de police (séparés par des virgules) pour le FallBack |
## Remarques

```cpp
// Créer une nouvelle instance de FantFallBackRule avec deux polices
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Créer une nouvelle instance de FantFallBackRule avec plusieurs polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)