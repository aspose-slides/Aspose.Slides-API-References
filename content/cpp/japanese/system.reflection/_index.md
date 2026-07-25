---
title: "System::Reflection"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 755
url: /ja/system.reflection/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) アセンブリを記述するクラスです。C# と C++ の規則がかなり異なるため、サポートは限定的です。このクラスのオブジェクトは、[System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーションエラーが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [AssemblyName](./assemblyname/) | アセンブリ名を定義します。このクラスのオブジェクトは、[System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーションエラーが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | 実行中のアセンブリに型を登録するシングルトンです。 |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | 実行中のアセンブリに型を登録するシングルトンの基底型です。 |
| [ConstructorInfo](./constructorinfo/) | コンストラクタのメタデータへのアクセスを提供します。 |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException は、モジュール内のクラスのいずれかのロードに失敗した場合に Module.GetTypes メソッドによってスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ReflectionTypeLoadException クラスを使用してください。ReflectionTypeLoadException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) にラップしないでください。 |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException は、リフレクションを通じて呼び出されたメソッドでスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに TargetInvocationException クラスを使用してください。TargetInvocationException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) にラップしないでください。 |
| [FieldInfo](./fieldinfo/) | フィールドの属性を検出し、フィールドのメタデータへのアクセスを提供します。 |
| [MemberInfo](./memberinfo/) | メンバーに関するリフレクション情報を提供します。このクラスのオブジェクトは、[System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーションエラーが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [MethodBase](./methodbase/) | メソッドに関する基礎情報です。このクラスのオブジェクトは、[System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーションエラーが発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [MethodInfo](./methodinfo/) | クラスメソッドに関する情報を表します。 |
| [PropertyInfo](./propertyinfo/) | プロパティ情報を表します。 |

## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [BindingFlags](./bindingflags/) | メンバーと型の検索モードおよびバインディングを定義します。 |
| [FieldAttributes](./fieldattributes/) | リフレクトされたフィールド属性です。 |
| [MemberTypes](./membertypes/) | 各メンバーのタイプにマークを付けます。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException は、モジュール内のクラスのいずれかのロードに失敗した場合に Module.GetTypes メソッドによってスローされます。ReflectionTypeLoadException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) にラップしないでください。 |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException は、リフレクションを通じて呼び出されたメソッドでスローされます。TargetInvocationException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) にラップしないでください。 |