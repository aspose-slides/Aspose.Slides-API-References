---
title: SlideShowTransition
second_title: Referência da API Aspose.Slides para C++
description: Representa a transição da apresentação de slides.
type: docs
weight: 404
url: /pt/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition classe

Representa a transição da apresentação de slides.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Métodos

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se as duas instâncias [SlideShowTransition](./) são iguais. Leitura/gravação **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Leitura **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Especifica o tempo, em milissegundos, após o qual a transição deve começar. Esta configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que não haverá avanço automático. Leitura **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Especifica se um clique de mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor true. Leitura **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Obtém a duração do efeito de transição do slide em milissegundos. Leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Retorna os dados de áudio incorporados. Leitura [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Especifica se este som é um som embutido ou não. Se este atributo for definido como true, a aplicação geradora é alertada para verificar o atributo name especificado para este som em sua lista de sons embutidos e pode então exibir um nome ou interface personalizada conforme necessário. Leitura **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Este atributo especifica se o som será reproduzido em loop até que ocorra o próximo evento sonoro na apresentação. Leitura **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Define ou retorna o modo de som para a transição de slide. Leitura [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Especifica um nome legível por humanos para o som da transição. O [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) deve ser atribuído para obter ou definir o nome do som. Leitura [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Especifica a velocidade de transição a ser usada ao transitar do slide atual para o próximo. Leitura [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Tipo de transição. Leitura [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) mostra o valor de transição. Somente leitura [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Serve como função de hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela de hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Gravação **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Esta configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que não haverá avanço automático. Gravação **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Especifica se um clique de mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor true. Gravação **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Define a duração do efeito de transição do slide em milissegundos. Gravação **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Define os dados de áudio incorporados. Gravação [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Especifica se este som é embutido ou não. Se este atributo for definido como true, a aplicação geradora é alertada para verificar o atributo name especificado para este som em sua lista de sons embutidos e pode então exibir um nome ou UI personalizada conforme necessário. Gravação **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Este atributo especifica se o som será reproduzido em loop até o próximo evento sonoro na apresentação. Gravação **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Define ou retorna o modo de som para a transição de slide. Gravação [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Especifica um nome legível por humanos para o som da transição. O [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) deve ser atribuído para obter ou definir o nome do som. Gravação [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Especifica a velocidade de transição a ser usada ao transitar do slide atual para o próximo. Gravação [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Tipo de transição. Gravação [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Espaço de nomes [Aspose::Slides::SlideShow](../)
* Library [Aspose.Slides](../../)