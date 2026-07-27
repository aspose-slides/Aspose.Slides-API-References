---
title: Thread
second_title: Referência da API Aspose.Slides para C++
description: "Implementação de Thread. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 209
url: /pt/system.threading/thread/
---
## Thread classe


[Thread](./) implementação. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre embrulhe esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Thread : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| void [Abort](./abort/)() | Aborta a thread. Não implementado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | Obtém a cultura da thread. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | Obtém o objeto que descreve a thread atual. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | Obtém a cultura da interface do usuário usada pela thread. |
| **bool** [get_IsAlive](./get_isalive/)() | Verifica se a thread está viva. |
| **bool** [get_IsBackground](./get_isbackground/)() | Verifica se a thread está em segundo plano. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Verifica se a thread é possuída por um pool de threads. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | Obtém o identificador da thread. Pode ser obtido do SO, mas se o identificador da thread do SO exceder os limites de int, os ids das threads podem se sobrepor. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | Obtém o nome da thread. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | Obtém o estado da thread. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | Obtém o identificador da thread atual. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Interrupt](./interrupt/)() | Interrompe a thread. Não implementado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Join](./join/)() | Une a thread gerenciada. Executa espera ilimitada se necessário. |
| **bool** [Join](./join/)(int) | Une a thread gerenciada. Executa espera limitada. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | Une a thread gerenciada. Executa espera limitada. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| static void [MemoryBarrier](./memorybarrier/)() | Sincroniza o acesso à memória. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | Copia dados TLS de outra thread. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Define a cultura da thread. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Define a cultura da interface do usuário usada pela thread. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | Define a thread como segundo plano ou primeiro plano. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | Define o nome da thread. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| static void [Sleep](./sleep/)(int) | Interrompe a thread atual por um tempo limite especificado. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | Interrompe a thread atual por um tempo limite especificado. |
| static void [SpinWait](./spinwait/)(int) | Aguarda um número específico de iterações de loop. |
| void [Start](./start/)() | Inicia a thread usando objeto de argumento nulo. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Inicia a thread. |
|  [Thread](./thread/)() | Construtor. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | Construtor. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | Construtor. |
|  [Thread](./thread/)([Thread](./)\&) | Construtor de cópia. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| static **bool** [Yield](./yield/)() | Cede a thread. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
| virtual  [~Thread](./~thread/)() | Destrutor. |
## Observações



```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
ID da thread principal: 2
ID da thread filha: 1
*/
```

## Ver também

* Classe [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)