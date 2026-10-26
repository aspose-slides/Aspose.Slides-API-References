---
title: SetLicense()
second_title: Aspose.Slides para C++ Referência da API
description: Licencia o componente.
type: docs
weight: 1
url: /pt/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) método


Licencia o componente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Pode ser um nome de arquivo completo ou abreviado ou o nome de um recurso incorporado. Use uma string vazia para mudar para o modo de avaliação. |
## Observações



Tenta encontrar a licença nos seguintes locais:

1. Caminho explícito.

2. A pasta da assembly do componente.

3. A pasta da assembly de chamada do cliente.

4. A pasta da assembly de entrada.

5. Um recurso incorporado na assembly de chamada do cliente.

**Nota:**No .NET Compact Framework, tenta encontrar a licença apenas nesses locais:

1. Caminho explícito.

2. Um recurso incorporado na assembly de chamada do cliente.

Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém a assembly de chamada, na pasta da assembly de entrada e, em seguida, nos recursos incorporados da assembly de chamada. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) método


Licencia o componente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo que contém a licença. |
## Observações



Use este método para carregar uma licença a partir de um fluxo.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ILicense](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)