#  JMBAG
   0036479475

Pitanje 1 
Pored .exe datoteke stvorena je i .dll datoteka. Ne može se pokrenuti jer fali potreban asemblij (dll) koji je poveznica glavnog programa sa korištenom bibliotekom . Poslat æu vam .exe datoteku i .dll. datoteku .

Pitanje 2
Konzolna aplikacija je koristila staru verziju class library asemblija, ispisao se isti tekst kao i prije, jer program nije ponovno preveden.

Pitanje 3
Pero: Hello World

Pitanje 4 
Nastao je .dll file PeroClassLibrary

Pitanje 5
Aplikacija radi jer potrebni .dll file ima u debug datoteci te se referencira na njeg.

Pitanje 6 
Aplikacija je buildana a u Solution je ponovno napravljen obrisani direktorij . Potrebno je samo da unutar packages.config postoji ID paketa koji se koristi i ako ne postoji on æe biti instaliran.