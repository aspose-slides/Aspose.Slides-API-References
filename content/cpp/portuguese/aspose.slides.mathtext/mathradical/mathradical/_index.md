---
title: MathRadical()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathRadical.
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) construtor


Inicializa uma nova instância da classe [MathRadical](../).

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Grau |
## Observações



Exemplo: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)