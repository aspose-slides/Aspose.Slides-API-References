---
title: Color
second_title: Αναφορά API Aspose.Slides για C++
description: "Αναπαριστά ένα χρώμα. Αυτός ο τύπος πρέπει να καταλαμβάνεται στη στοίβα και να περνάται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 53
url: /el/system.drawing/color/
---
## Κλάση Color

Αναπαριστά ένα χρώμα. Αυτός ο τύπος θα πρέπει να καταλαμβάνεται στη στοίβα και να περνάται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../../system/smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
class Color
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [Color](./color/)() | Κατασκευάζει ένα "κενό" αντίγραφο της κλάσης [Color](./) που δεν αντιπροσωπεύει κανένα χρώμα. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Καθορίζει αν το τρέχον και το συγκεκριμένο αντικείμενο [Color](./) αντιπροσωπεύουν το ίδιο χρώμα. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Κατασκευάζει ένα αντίγραφο της κλάσης [Color](./) που αντιπροσωπεύει το καθορισμένο χρώμα. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Κατασκευάζει ένα αντίγραφο της κλάσης [Color](./) που αντιπροσωπεύει το καθορισμένο χρώμα. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Κατασκευάζει ένα αντίγραφο της κλάσης [Color](./) που αντιπροσωπεύει το καθορισμένο χρώμα με το συστατικό άλφα ορισμένο στο 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Κατασκευάζει ένα αντίγραφο της κλάσης [Color](./) που αντιπροσωπεύει το καθορισμένο χρώμα. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Κατασκευάζει ένα αντίγραφο της κλάσης [Color](./) που αντιπροσωπεύει το καθορισμένο γνωστό χρώμα. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Κατασκευάζει ένα αντίγραφο της κλάσης [Color](./) που αντιπροσωπεύει ένα χρώμα με το καθορισμένο όνομα. |
| int [get_A](./get_a/)() const | Επιστρέφει την τιμή του συστατικού άλφα του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF0FFFF. |
| int [get_B](./get_b/)() const | Επιστρέφει την τιμή του μπλε συστατικού του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [Color](./) [get_Beige](./get_beige/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF00FF. |
| int [get_G](./get_g/)() const | Επιστρέφει την τιμή του πράσινου συστατικού του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Επιστρέφει μια τιμή που υποδεικνύει αν το τρέχον αντικείμενο είναι "κενό", δηλαδή δεν αντιπροσωπεύει κανένα χρώμα. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Επιστρέφει μια τιμή που καθορίζει αν η δομή [Color](./) αντιπροσωπεύει ένα ονομαστικό χρώμα ή ένα μέλος της αρίθμησης KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Επιστρέφει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Επιστέ��ει το όνομα του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF800080. |
| int [get_R](./get_r/)() const | Επιστέ��ει την τιμή του κόκκινου συστατικού του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [Color](./) [get_Red](./get_red/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARBG σε δεκαεξαδική σημειογραφία είναι #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARGB σε δεκαεξαδική σημειογραφία είναι #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARBG σε δεκαεξαδική σημειογραφία είναι #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARBG σε δεκαεξαδική σημειογραφία είναι #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Επιστέ��ει ένα χρώμα του οποίου η τιμή ARBG σε δεκαεξαδική σημειογραφία είναι #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Επιστέ��ει το συστατικό φωτεινότητας του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| int [GetHashCode](./gethashcode/)() const | Επιστέ��ει τον κωδικό κατακερματισμού του τρέχοντος αντικειμένου. |
| **float** [GetHue](./gethue/)() | Επιστέ��ει την τιμή του αποχρώματος (Hue) στο μοντέλο Hue-Saturation-Brightness (HSB), σε μοίρες, για το χρώμα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **float** [GetSaturation](./getsaturation/)() | Επιστέ��ει την τιμή του κορεσμού (Saturation) στο μοντέλο Hue-Saturation-Brightness (HSB) για το χρώμα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsNull](./isnull/)() const | Επιστέ��ει πάντα ψευδές. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Επιστέ��ει πάντα αληθές. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Καθορίζει αν το τρέχον και το συγκεκριμένο αντικείμενο [Color](./) αντιπροσωπεύουν διαφορετικά χρώματα. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Επιστέ��ει πάντα ψευδές. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Καθορίζει αν το τρέχον και το συγκεκριμένο αντικείμενο [Color](./) αντιπροσωπεύουν το ίδιο χρώμα. |
| int [ToArgb](./toargb/)() const | Επιστέ��ει μια 32-bit τιμή ARGB του χρώματος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../../system/string/) [ToString](./tostring/)() const | Επιστέ��ει τη συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [Empty](./empty/) | Ένα "κενό" αντίγραφο της κλάσης [Color](./), δηλαδή ένα αντίγραφο που δεν αντιπροσωπεύει κανένα χρώμα. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Drawing](../)
* Βιβλιοθήκη [Aspose.Slides](../../)