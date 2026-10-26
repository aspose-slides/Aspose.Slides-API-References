---
title: AddFallBackFonts()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona nova(s) fonte(s) à lista de fontes FallBack.
type: docs
weight: 79
url: /pt/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) método

Adiciona nova(s) fonte(s) à lista de FallBack fonts.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome ou nomes da fonte (separados por vírgula) para FallBack |
## Observações

```cpp
// Crie uma nova instância de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Adicione uma segunda fonte à regra
newRule->AddFallBackFonts(u"MS Gothic");
//Adicione a terceira e a quarta fontes à regra
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) método

Adiciona novas fontes à lista de FallBack fonts.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nome ou nomes da fonte (separados por vírgula) para FallBack |
## Observações

```cpp
// Crie uma nova instância de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Adicione mais três fontes à regra
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)