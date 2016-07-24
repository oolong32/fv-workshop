## Zeitaufand Planung, Vorbereitung, Durchführung

- Konzeption
- Online Dokumentation
- Handout für Teilnehmer
    - Handout Markup
        - Syntax
        - Beispiele
        - weiterführende Information
    - Handout Github
        - Übersicht
        - Funktionen
        - weiterführende Information
- Planung Workshop
    - Input
        - Recherche Themen
        - Ablauf/Zeitplan
        - Vorbereitung Keynote
        - Erstellen Keynote
    - Übungsteil 
        - Definieren der zu vermittelnden Kompetenzen
        - Erarbeitung Übung (gemeinsame Arbeit an einem Text zu bestimmtem Thema)
        - Vorbereitung für Auswertung und Besprechung am Schluss
- Durchführung Workshop, Dauer zu bestimmen (ein Tag oder zwei Tage)
- Nachbearbeitung
    - Dokumentieren der Erfahrung
        - was war gut?
        - was ist zu verbessern?
    - Nachbearbeitung Hand-Outs
    - Nachbearbeitung Online Dokumentation
- Dokumentation der gesamten Arbeit am Workshop

## Einleitung

Dozierende verbringen üblicherweise einen grossen Teil der Zeit, in der Sie ihren Unterricht vorbereiten, mit dem Sammeln und Aufbereiten von Information. Zusammentragen von Texten, Bildern und Filmen, Erstellen von Listen mit Buchtiteln, Links und Adressen etc.

Arbeiten sie in einem Team, muss die Information ausgetauscht werden. Es entstehen verschiedene Versionen der gleichen Inhalte an unterschiedlichen Orten, Textdateien werden in andere Formate übertragen, als PDF exportiert etc.

Zuletzt müssen sie die aufbereitete Information Studenten, Mitarbeitern etc. zugänglich gemacht werden: Texte müssen in les- und überschaubare Form gebracht werden. Und dann stellt sich die Frage, in welcher Art und Weise die Information kommuniziert wird.

Software, die dem Zweck gerade knapp genügt, ist kein Werkzeug, sonern wird zur Krücke: Man kommt nicht vorwärts. Das Durcheinander von Formaten und Versionen verlangsamt die Arbeit zusätzlich.

### Einige Beispiele

* Information, die per E-Mail verschickt wurde, verschwindet in den Abgründen des elektronischen Posteingangs. Monate später sucht man nach Stichworten, an die man sich nur bruchstückhaft erinnert und muss sich durch Antworten auf Weiterleitungen kämpfen, bis man das ursprüngliche Mail mit intaktem Inhalt findet.
* Text im PDF-Format kann nicht sauber kopiert und in ein neues Dokument eingefügt werden, weil z.B. Zeilenumbrüche zu harten Umbrüchen werden, die von Hand korrigiert werden müssen.
* Es ist nicht mehr klar, wer die aktuellste Version des gemeinsam erstellten Dokuments besitzt.
* Irrational beschriftete Dateien mit in X Formaten häufen sich auf dem Schreibtisch, im Browser bleiben Tabs dutzendweise wochenlang geöffnet.

## Professionelle Werkzeuge

Die obengenannten Phänomene sind nicht unvermeidliche Konsequenzen des Arbeitens mit dem Computer, sie sind auch nicht das selbstverschuldete Elend des ungeschickten Benutzers. Sie sind vielmehr Symptome für die Arbeit mit Werkzeugen, die dem Zweck nicht genügen. Es muss gesagt werden: eine Vielzahl der Software, mit der wir arbeiten, taugt nicht besnoders viel. Mit Word kann man zwar Geschäftsbriefe schreiben. Für profesionelles Arbeiten mit Text ist es nicht geeignet. PDF ist ein Dateiformat, um Printsachen an die Druckerei zu schicken. Zur Übermittlung von Textinformation, die weiterverarbeitet werden soll, ist es das falsche Mittel.

Ich möchte zwei Werkzeuge vorstellen, mit denen ich für die Recherche, für den Austausch mit anderen Dozierenden und für die Publikation sehr gute Erfahrungen gemacht habe. Das Erste erleichtert das Erstellen sauber strukturierter Texte, die auch Links und Bilder enthalten können. Das Zweite dient zwei Zwecken. Einerseits der Arbeit an Dokumenten im Team, andererseits der Publikation dieser Dokumente im Web. Diese beiden Werkzeuge existieren unabhängig voneinander, in Kombination ergeben sie aber ein äusserst effizientes Gespann.

### Vorteile gegenüber «herkömmlicher» Software

*
*
*

## Erstes Werkzeug: Markdown

[Markdown](https://daringfireball.net/projects/markdown/) ist eine sehr einfache Auszeichnungssprache. Sie kommt mit einem sehr limitierten Zeichensatz aus: dem Bindestrich (\-), dem Asterisk (\*), der Raute (\#), runden \(\) und eckigen \[\] Klammern. Die Syntax ist so simpel und reduziert, dass sich Text schnell auszeichnen lässt und auch nach erfolgter Auszeichnung gut lesbar bleibt.

Die Möglichkeit, einerseits Links und Bilder einzufügen und andererseits Texte leicht ins HTML-Format zu exportieren, machen *Markdown* zu einem Werkzeug, das auf die Erfordernisse der Arbeit mit Quellen und Publikationskanälen im Web zugeschnitten ist.

### Zum Begriff «Auszeichnungssprache»

Eine *Auszeichnugssprache* (engl. ‘markup language’) ist ein Zeichenset, welches dazu dient, einen Text mit strukturgebender Information zu versehen. Im Unterschied zu [Rich Text](https://de.wikipedia.org/wiki/Rich_Text_Format) und ähnlichen Dateiformaten, die bereits am Bilschirm die Ausgabe nach dem Druck simulieren, werden Textteile nicht durch Farbe, Schriftgewicht, -grösse oder -schnitt ausgezeichnet. Es wird lediglich angegeben, ob ein Textelement asugezeichnet werden soll z.B. ob es sich um eine Überschrift, um eine Liste oder um ein hervorzuhebendes Wort handelt. So wird Text organisiert, z.B. indem Hierarchien definiert werden. Er wird aber nicht mit typographischen Mitteln formatiert – die Angaben zu Auszeichnung bleiben distinkt.

Ein Vorteil der Verwendung einer Auszeichnungssprache ist beispielsweise, dass ein Text schnell in sehr unterschiedliche Formate exportiert werden kann, z.B. in DIN A4 PDF zum Drucken, und gleichzeitig in ein Web-taugliches Format wie HTML. Viele Online Plattformen unterstützen mittlerweile *Markdown* und auch für Desktop Publishing Software wie *InDesign* existieren [Plugins](http://www.jongware.com/markdownid.html), die einen Import erlauben.

Ein weiterer Vorteil ist die Flexibilität in der Gestaltung: Wie ein ausgezeichneter Textteil wiedergegeben wird – ob kursiv oder fett, schwarz oder rot, gross oder klein – kann zu einem späteren Zeitpunkt, bzw. immer wieder neu definiert werden, ohne den eigentlichen Text manipulieren zu müssen.

Ein unmittelbarer Vorteil von *Markdown* erwächst aus der äusserst reduzierten und simplen Syntax: Man zeichnet Text aus, ohne die Finger beim Schreiben von den Tasten zu lösen – der Schreibfluss gestaltet sich um ein Vielfaches effizienter als bei der Verwendung einer herkömmlichen Textverarbeitungssoftware.

### Möglichkeiten der Verwendung

Ich selber verwende Markdown grundsätzlich für alle Textdokumente, von denen ich noch nicht weiss, in welcher Form ich sie publizieren werde. Ich schreibe *Markdown* sowohl in einfachen Programmen wie *TextEdit* als auch in komplexeren Texteditoren wie [Vim](http://www.vim.org/).

Die Texte exportiere ich je nach Bedarf als PDF oder als HTML-Dokumente. Bei Bedarf bearbeite sie in InDesign weiter, oder publiziere sie auf *GitHub*. In der Regel schreibe ich ohne Vorschau, es kommt aber vor, dass ich Software wie [Mou](http://25.io/mou/) und [Marked](http://marked2app.com/) verwende, wenn ich eine Art «reingeschriebene» Fassung sehen möchte.

Sehr bewährt hat sich das Einfordern von Hausaufgaben im *Markdown* Format. Dadurch kann ich Beiträge meiner Studierenden in kürzester Zeit zusammenführen, kommentieren und ins Netz stellen. Gleichzeitig ist eine einheitliche Struktur gewährleistet. Die Studierenden müssen Markdown natürlich zu Kursbeginn erlernen. Durch den geringen Aufwand war die Resonanz bisher aber jeweils gut.

## Zweites Werkzeug: GitHub

[GitHub](https://github.com/) ist eine Online-Plattform zur Speicherung und zum Austausch von Code. Sie basiert auf einer Software namens «[Git](https://git-scm.com/)», die wiederum der sog. [Versionsverwaltung](https://de.wikipedia.org/wiki/Versionsverwaltung) von Code dient. Mit «Code» ist hier programmierter Quelltext gemeint. Sowohl *Git* als auch *GitHub* wurden geschaffen, um Probleme zu lösen, die beim Programmieren von Software anfallen.

Nun ist das Programmieren von Software eine bestimmte Form des Schreibens von Text und so mag es nicht erstaunen, dass sowohl *Git* als auch *GitHub* für Autoren aller Art von grossem Nutzen sein können.

### Git

Wir werden *Git* nicht näher betrachten, vollständigkeitshalber beschreibe ich aber kurz, um was es geht: Beim Schreiben von Software arbeitet man in der Regel mit einer bestimmten Anzahl Dateien, die jeweils einen Teil des Quelltextes enthalten: Vielleicht legt die Länge des Quelltextes eine Teilung in mehrere Dokumente nahe, vielleicht gilt es, funktionalen Unterschieden Rechnung zu tragen oder es werden verschiedene Programmiersprachen kombiniert. Jedes Dokument gliedert sich wiederum in Sektionen, Teilbereiche, Kommentare etc. Kurz: Es handelt sich um komplexe Texte.

Diese Teile des Quelltextes müssen laufend gerüft und angepasst werden. Im Verlauf eines Projektes tritt eine Vielzahl von Problemstellungen auf. Diese werden in der Regel in eine Reihe untergeordneter Probleme gegliedert, die der Reihe nach behandelt werden. Dadurch ergeben sich grundlegende, übergeordnete Fragen: Was geschieht, wenn man nach einer Reihe von Änderungen merkt, dass man sich unterwegs verrannt hat? Wie kommt man auf die letzte funktionierende Version zurück? Was, wenn in der Zwischenzeit andere Programmierer an den gleichen Dokumeten weitergearbeitet haben?

*Git* ist eine Software, die Änderungen an Dateien aufzeichnet. Es ist zu jedem Zeitpunkt möglich, zu einer bestimmten Version zurückzukehren. Dazu lassen sich Projekte in verschiedene Zweige aufgliedern: Es können gleichzeitig komplett verschiedene Versionen des Quelltexts existieren, die zu einem späteren Zeitpunkt wieder zusammengeführt werden können. *Git* ist ein Werkzeug, das Ordnung herstellt, gleichzeitig ist es eine Versicherung für den Fall, dass der Quelltext durch Fehlleistungen Schaden nimmt.

### GitHub

Die Web Site *GitHub* dient als Publikationskanal für Projekte, die mit *Git* verwaltet werden. Um Information über *GitHub* zu publizieren, ist die Verwendung von *Git* aber nicht zwingend notwendig: Ein neues Projekt – genannt «Repository» – kann online erstellt werden. Die Handhabung ist im Vergleich zu *Git* viel einfacher.

*GitHub* bietet verschiedene Funktionen, die das gemeinsame Arbeiten an Quelltext erleichtern. So ist es zum Beispiel möglich, mehreren Autoren die Arbeit an einem Dokument zu erlauben. Es ist auch möglich als Unbeteiligter Meldungen zu einem Dokument zu machen, um Wünsche zu äussern oder um auf Probleme hinzuweisen. Allen Funktionen liegt ein System zugrunde, die das Referenzieren und Zurordnen erleichtert, was wiederum gewährleistet, dass auch bei zig Mitarbeitern immer klar ist, wer wann was gemacht hat.

Für Schriftsteller, Künstler und Dozierende ist (fürs Erste) vor allem die Möglichkeit attraktiv, Texte online publizieren zu können, an denen gemeinsam gearbeitet werden kann.

Das schöne an *GitHub* ist, dass mit *Markdown* ausgezeichnete Texte sauber gelayoutet wiedergegeben werden. Dadurch ergibt sich ein effizienter und direkter Arbeitsfluss von der Recherche zur Publikation.


#### Repository

Als *Repository* wird die oberste Ebene eines Projekts bezeichnet.

#### Branch
#### Commits
#### Pull Request
#### Merge
#### Issues
#### …
#### Publikation Website statt Markdown-Dokument

## Links

* [Github – Basic Tutorial](https://guides.github.com/activities/hello-world/)

## Möglicher zusätzlicher Workshop: Keynote

Die Dozierenden im CAS Digital Typography verwenden für Präsentationen im Unterricht alle Keynote. Wir haben damit äusserst gute Erfahrungen gemacht. Ich kenne sehr viele Leute innerhalb der ZHdK, die Keynote nicht oder nur unzureichend beherrschen, ev. könnte das also auch ein Thema sein?
