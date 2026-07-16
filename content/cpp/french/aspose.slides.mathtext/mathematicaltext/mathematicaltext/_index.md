---
title: MathematicalText()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Constructeur par défaut (crée la valeur String::Empty)"
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() constructeur


Constructeur par défaut (crée la valeur String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Remarques


Exemple:
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) constructeur


Créer [MathText](../../) avec un symbole unique

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | symbole unique |
## Remarques



Exemple:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) constructeur


Créer [MathematicalText](../) à partir du texte

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valeur du texte |
## Remarques



Exemple:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) constructeur


Créer [MathematicalText](../) à partir du texte et des paramètres de format du texte

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valeur du texte |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | paramètres de format du texte |
## Remarques



Exemple:
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [MathematicalText](../)
* Classe [String](../../../system/string/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)