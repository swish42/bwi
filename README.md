# BWI challenge
Zwei Transporter mit bestimmter Ladekapazität sollen optimal beladen werden. Für jedes Gerät, das in die Transporter geladen werden soll, stehen Gewicht und Nutzwert zur Verfügung.

### Algorithmus
Das Programm löst das Problem zunächst mit einem Greedy-Algorithmus, der die Geräte nach ihrem Profit = Nutzwert/Gewicht einpackt und dabei die Transporter abwechselnd belädt. Danach wird mit dynamischer Programmierung eine bessere Lösung gesucht und gefunden.

### Lösung
{'Mobiltelefon Outdoor': 79, 'Mobiltelefon Heavy Duty': 110, 'Mobiltelefon Büro': 28, 'Tablet outdoor groß': 185, 'Tablet Büro klein': 304, 'Tablet Büro groß': 0, 'Tablet outdoor klein': 1, 'Notebook outdoor': 0, 'Notebook Büro 13"': 0, 'Notebook Büro 14"': 0}
{'Mobiltelefon Outdoor': 78, 'Mobiltelefon Heavy Duty': 110, 'Mobiltelefon Büro': 31, 'Tablet outdoor groß': 185, 'Tablet Büro klein': 295, 'Tablet Büro groß': 0, 'Tablet outdoor klein': 0, 'Notebook outdoor': 0, 'Notebook Büro 13"': 0, 'Notebook Büro 14"': 0}
Gewicht 1: 1027438
Wert 1: 37515
Gewicht 2: 1014266
Wert 2: 37140
Gewicht 1+2: 2041704
Wert 1+2: 74655

### Ausführung
Zunächst
```
python -m notebook
```
und dann das Notebook `bwi` auswählen.
