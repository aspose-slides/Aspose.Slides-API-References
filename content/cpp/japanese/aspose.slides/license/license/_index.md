---
title: License()
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスの新しいインスタンスを初期化します。
type: docs
weight: 1
url: /ja/aspose.slides/license/license/
---
## License::License() コンストラクタ


このクラスの新しいインスタンスを初期化します。

```cpp
Aspose::Slides::License::License()
```

## 備考


この例では、コンポーネントが含まれるフォルダー、呼び出し元アセンブリが含まれるフォルダー、エントリ アセンブリのフォルダー、そして呼び出し元アセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンス ファイルを検索しようとします。 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## 参照

* クラス [License](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)