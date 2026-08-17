---
title: EmbeddingLevel
second_title: Aspose.Slides の Java API リファレンス
description: フォントを埋め込むためのライセンス権を表します。
type: docs
url: /ja/com.aspose.slides/embeddinglevel/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

フォントの埋め込みに関するライセンス権を表します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Installable](#Installable) | この設定が付いたフォントは、アプリケーションによって埋め込まれ、リモートシステムに永続的にインストールできることを示します。 |
| [Restricted](#Restricted) | このビットだけが設定されているフォントは、法的所有者の許可を事前に取得せずに、いかなる方法でも変更、埋め込み、または交換してはなりません。 |
| [PreviewPrint](#PreviewPrint) | このビットが設定されている場合、フォントは埋め込むことができ、リモートシステムに一時的にロードされます。 |
| [Editable](#Editable) | このビットが設定されている場合、フォントは埋め込むことができますが、他のシステムに一時的にのみインストールする必要があります。 |
| [NoSubsetting](#NoSubsetting) | このビットが設定されている場合、フォントは埋め込む前にサブセット化できません。 |
| [BitmapOnly](#BitmapOnly) | このビットが設定されている場合、フォントに含まれるビットマップのみが埋め込むことができます。 |
### インストール可能 {#Installable}
```
public static final int Installable
```

この設定が付いたフォントは、アプリケーションによって埋め込まれ、リモートシステムに永続的にインストールできることを示します。リモートシステムのユーザーは、そのフォントに対して元の購入者と同一の権利、義務、ライセンスを取得し、元の購入者と同様のエンドユーザー使用許諾契約、著作権、意匠特許、または商標の対象となります。

### 制限付き {#Restricted}
```
public static final int Restricted
```

このビットだけが設定されているフォントは、法的所有者の許可を事前に取得せずに、いかなる方法でも変更、埋め込み、または交換してはなりません。

### プレビュー印刷 {#PreviewPrint}
```
public static final int PreviewPrint
```

このビットが設定されている場合、フォントは埋め込むことができ、リモートシステムに一時的にロードされます。Preview & Print フォントを含むドキュメントは「読み取り専用」で開く必要があり、文書に対して編集を加えることはできません。

### 編集可能 {#Editable}
```
public static final int Editable
```

このビットが設定されている場合、フォントは埋め込むことができますが、他のシステムに一時的にのみインストールする必要があります。Preview & Print フォントとは異なり、Editable フォントを含むドキュメントは読み取り用に開くことができ、編集が許可され、変更を保存できます。

### サブセット不可 {#NoSubsetting}
```
public static final int NoSubsetting
```

このビットが設定されている場合、フォントは埋め込む前にサブセット化できません。ビット0〜3および9で指定された他の埋め込み制限も適用されます。

### ビットマップのみ {#BitmapOnly}
```
public static final int BitmapOnly
```

このビットが設定されている場合、フォントに含まれるビットマップのみが埋め込むことができます。アウトラインデータは埋め込めません。フォントにビットマップがまったく含まれていない場合、そのフォントは埋め込み不可能と見なされ、埋め込みサービスは失敗します。