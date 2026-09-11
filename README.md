## Lernperiode 11

14.8 bis 11.9.2024

## Grob-Planung

1. Erklären Sie Ihre Projekt-Idee in einem Satz, als müssen Sie einen Investor davon überzeugen.
   Funktionale Französisch Vokabeln und Verben App, mit der man die Verben konjugieren üben kann.
3. Erklären Sie, welche technischen Herausforderungen Sie in Ihrem Projekt erwarten.
   Ich denke mit dem neuen Framework Avalonia zu arbeiten und da alles zu verstehen wird die grösste herausforderung
5. Beschreiben Sie, welche nicht-technischen Aspekte Sie in diesem Projekt besonders üben möchten.
   
7. Wie unterscheidet sich dieses Projekt von Ihrem Projekt in 335; und wo ergänzen sich diese Projekte?

## Feriges Projekt
In meinem Französichtrainer kann man Verben konjugieren und Vokabeln üben. 


<img width="800" height="1358" alt="image" src="https://github.com/user-attachments/assets/ed4617a5-94af-4226-b29c-13ec641f5385" />

Verben konjugieren:
<img width="794" height="1364" alt="image" src="https://github.com/user-attachments/assets/925e7e0d-fe4b-4c6e-8ec4-4e3e2dffb11a" />

Das Auswertungsfenster:
<img width="886" height="1352" alt="image" src="https://github.com/user-attachments/assets/9bd7d846-b1f2-4e64-a5ea-90f90027cfdf" />

Vokabeln:
<img width="1600" height="950" alt="image" src="https://github.com/user-attachments/assets/6ec51afd-ccef-484f-89b1-4f1767290dcc" />

Man kann in den json Dateien immer mehr Wörter hinzu fügen.

### Verbesserungs Möglichkeiten: 
Dem Programm fehlt noch die Scrollfunktion. Dann wäre es passsend das es die Wörter direkt kontrolliert und man das Wort direkt nochmal muss schreiben. Zum lernen sollte es auch verschiedene Runden geben wo die Wörter wiederholt werden wo man oft falsch macht. Das Programm sollte auch den Lernstand speichern damit man an dem Punkt weiter machen kann wo man aufgehört hat. Man soll auch die Möglichkeit haben den Lernprozess von neu zu starten. Es soll auch noch eine Liste haben wo man alle Wörter schön aufgeklistet mit den Überstzungen/konjugationen aufgezeigt ist.

## 14.8

- [x] Als Schlülerin möchte ich Avalonia installiert haben damit ich mit meinem Projekt starten kann.
- [x] Als Inforamtikerin möchte ich mich über  das Framework Avalonia informieren damit ich in zununft und in diesem Projekt gut damit arbeiten kann. 
- [x] Als Informatikerin will ich das gelernte über Avalonia in einen kleinen Code umwandeln.

✍️ Heute habe ich... (50-100 Wörter)
mir überlegt was meine erste App sein sollte und mit welche Framework ich arbeiten will. Zum Anfangen habe ich geplant einen Vokabel/Verben übungs App(Französisch) zu machen. Ich habe mich dann für das Framework Avalonia entschieden weil ich in einem anderem Projekt dann mit NET. Maui arbeiten will. So habe ich zwie verschiedene Frameworks zum lernen. Dann habe ich Avalonia installiert und mich auf ihrer Webseite informiert was überhaupt Avalonia machen kann. Dann habe ich angefangen ein Tutorial von AValonia angefangen um zu schauen wie in diesem Framework programmiert wird. ICh habe ein Butten hinzugefügt, ein eingabefeld gemacht und das Layout mit dem grid und Farben gemacht.    


 ## 21.08

 - [x] Als Informatikerin werde ich versuchen ein das grobe Design derr App zu Skizzieren.
 - [x] Als Informatikerin werde ich anfangen die ersten Buttons zu Programmieren, damit meine Vokabel App schon mal was hat
 - [x] ALs Informatikerin kann ich dann den Buttons Funktionen geben damit Sie etwas bewirken.
 - [ ] Als Informatikerin werde ich versuchen das Design im Code umzusetzen.
☝️ Vergessen Sie nicht, einen ersten Code und Skizze auf github hochzuladen!
Arbeitspaket dezentral: Ich habe ein grobes Design gemacht wie meine Französisch trainings App sollte aussehen. Dabei habe ich die 3 verschiedenen Bildschirmmöglichkeiten designt:

<img width="1200" height="1600" alt="WhatsApp Image 2026-08-20 at 17 57 48" src="https://github.com/user-attachments/assets/3abcaa79-7257-4a3c-b784-e467a2cf3566" />

Heute habe die Buttons zu meiner App angepasst. Dann habe ich angefangen zu recherchieren wie man die Buttons zum Funktionieren bringt. Mit den Avalonia Tutorials: https://docs.avaloniaui.net/controls/  leider habe ich eine ganze Zeit nichts gefunden dann habe ich auch noch KI gefragt die hat auch so Codebeispiele gegeben, dei habe aber auch nciht wirklich funktioniert. IDese Funktion 
```
public VerbenWindow()
  {
      InitializeComponent();
  }
 ```
 funktioniert irgendwie nicht und ich weis nicht wieso. Dann habe ich noch am Design gearbeitet, musste es dann aber wieder löschen weil ich dachte vielleicht liegt es hier am  Problem das die Funktion nicht geht. 

## 28.08

- [x] Als Entwickler möchte ich die Ursache beim Fenster-Laden beheben, damit die App stabil startet
- [x] Als Benutzer möchte ich auf die Buttons klicken können, um Aktionen auszuführe
- [x] Als Benutzer möchte ich eine übersichtliche Oberfläche nach Mockup-Vorgabe sehen.

Heute habe ich den Fehler beim Fenster-Laden behoben und die Event-Handler für die Buttons im MainWindow korrigiert, sodass sich VerbenWindow und VokabelnWindow zuverlässig öffnen. Danach habe ich den XAML-Code für zwei Ansichten (Hauptmenü, Übungs-Bildschirm) exakt nach meiner Mockup-Skizze mit Grid, StackPanel und passenden Controls aufgebaut.

## 04.09

- [x] Als Benutzer möchte ich im Übungs-Bildschirm ein zufälliges Verb samt Personalpronomen angezeigt bekommen, um zu wissen, was ich konjugieren muss.
- [x] Als Benutzer möchte ich meine Lösung in das Eingabefeld eintippen und mit dem Button «Überprüfen» kontrollieren können.
- [x] Als Entwickler möchte ich die Logik für die Punkteberechnung programmieren, damit richtige und falsche Eingaben korrekt gezählt werden.
- [x] Als Benutzer möchte ich am Ende der Übung automatisch zur Auswertungsseite weitergeleitet werden, um meine Fehlerliste zu sehen.

Dezentral Arbeitspaket: Ich habe eine json Datei hinzugefügt mit der jetzt das Programm verbunden ist und immer random ein Verb herausnimmt und anzeigt. Das Pronomen auch random zugeteilt. Bis jetzt ist alles noch im infinitiv.
Ich habe das Eingabefeld mit dem Button „Überprüfen“ verbunden und die Lösungen der Verben in der JSON-Datei ergänzt. Die eingegebene Antwort wird nun kontrolliert und als richtig oder falsch gezählt. Nach zehn Aufgaben öffnet sich automatisch die Auswertungsseite, auf der die erreichten Punkte und alle Fehler mit den richtigen Lösungen angezeigt werden.

## 11.09

- [x] Als Benutzerin möchte ich, dass die Texte auf der Auswertungsseite eine gut sichtbare Farbe besitzen, damit ich die Punkte und die Fehlerliste problemlos lesen kann.
- [ ] Als Entwicklerin möchte ich die Vokabeln in einer JSON-Datei speichern und diese mit dem Vokabeltrainer verbinden, damit neue Vokabeln einfach hinzugefügt und vom Programm geladen werden können.
- [ ] Als Benutzerin möchte ich das die VOkabeln in einer Runde nur einmal drankommt, damit ich nicht immer die gleihcen bekomme.
dezentral: Ich habe das erste arbeitspaket gemacht: Somit kann man jetzt den Text auf der auswertungsseite auch wirklich lesen. Auch das VErb beim Abfragen ist nun lesbar, in dem ich die farb codes gändert habe. In einer RUnde kommen alle wörter dran und auch nie doppelt. Sie werden wie beim Verben konjugieren am shcluss korriegiert und das Resultat wird angezeigt.
Ich habe das Vokabeln PRogramm zum funktionieren gebracht. ICH ahbe ein json Datei mit wichtigen Wörter gefüllt die jetzt im Programm abgefragt werden.


