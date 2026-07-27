---
title: ISlideShowTransition
second_title: Referência da API Aspose.Slides para C++
description: Representa a transição de apresentação de slides.
type: docs
weight: 3810
url: /pt/aspose.slides/islideshowtransition/
---
## ISlideShowTransition classe


Represents slide show transition.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Lê **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Essa configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que nenhum avanço automático ocorrerá. Lê **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor verdadeiro. Lê **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | Obtém a duração do efeito de transição do slide em milissegundos. Lê **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Retorna os dados de áudio incorporados. Lê [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | Especifica se este som é ou não um som embutido. Se este atributo for definido como verdadeiro, a aplicação geradora é notificada para verificar o atributo name especificado para este som em sua lista de sons embutidos e pode então apresentar um nome ou UI personalizados conforme necessário. Lê **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | Este atributo especifica se o som será repetido até que ocorra o próximo evento de som na apresentação. Lê **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | Define ou retorna o modo de som para a transição de slide. Lê [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | Especifica um nome legível por humanos para o som da transição. O [ISlideShowTransition::set_Sound](./set_sound/) deve ser atribuído para obter ou definir o nome do som. Lê [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | Especifica a velocidade da transição a ser usada ao passar do slide atual para o próximo. Lê [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | Tipo de transição. Lê [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) valor de transição de exibição. Somente leitura [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Escreve **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Essa configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que nenhum avanço automático ocorrerá. Escreve **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor verdadeiro. Escreve **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | Define a duração do efeito de transição do slide em milissegundos. Escreve **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Define os dados de áudio incorporados. Escreve [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | Especifica se este som é ou não um som embutido. Se este atributo for definido como verdadeiro, a aplicação geradora é notificada para verificar o atributo name especificado para este som em sua lista de sons embutidos e pode então apresentar um nome ou UI personalizados conforme necessário. Escreve **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | Este atributo especifica se o som será repetido até que ocorra o próximo evento de som na apresentação. Escreve **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | Define ou retorna o modo de som para a transição de slide. Escreve [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | Especifica um nome legível por humanos para o som da transição. O [ISlideShowTransition::set_Sound](./set_sound/) deve ser atribuído para obter ou definir o nome do som. Escreve [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | Especifica a velocidade da transição a ser usada ao passar do slide atual para o próximo. Escreve [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | Tipo de transição. Escreve [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)