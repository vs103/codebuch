# 226309 PV Grundlagen sozialer Netzwerkanalyse

# Datensatz Spaetzle-Connection-Regierung-Scholz
Codebuch Stand 2022-02, aktualisiert 2022-02
erstellt von Vanessa Stagen (vs103)

## Inhalt
- Nodes.csv (Nodelist)
- Edges.csv (Edgelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung der Datenerhebung
https://www.bundestag.de/
Gegencheck: https://www.abgeordnetenwatch.de/

# NODE-Attribute

**id** 
(identisch mit edgelist, aber hier nur einmalige Nennung)

**name_short** 
(Nachname)

**name** 
(voller Name)

**type**
0 = Person
1 = Organisation/Ort/Verband etc.

**sex** 
(Geschlecht)
1 = männlich 
2 = weiblich

**birth** 
(Geburtsjahr)

**position** 
(jetzige Position, z.B. Staatssekretär:in, Minister)
1 = Parlamentarischer Staatssekretär
2 = Staatsminister
3 = Bundesminister

**education** 
(höchster Bildungsabschluss)
1 = Diplom
2 = Staatsexamen
3 = Promotion
4 = Magister

**subject** 
(Fachrichtung bei Studium/Promotion)
1 = Wirtschaftswissenschaften
2 = Rechtswissenschaften
3 = Sozialwissenschaften
4 = Politikwissenschaften


**party** 
(Parteizugehörigkeit)
1 = FDP
2 = SPD
3 = Die Grüne

**religion** 
(Religion)
1 = römisch-katholisch 
2 = evangelisch
3 = muslimisch

**kids** 
(Anzahl der Kinder)

**twitter** 
(Anzahl follower)
1 = 1-499
2 = 500-4999
3 = 5000-19.999
4 = 20.000-99.999
5 = 100.000-299.999
6 = 300.000+

**instagram** 
(Anzahl follower)
1 = 1-499
2 = 500-4999
3 = 5000-19.999
4 = 20.000-99.999
5 = 100.000-299.999
6 = 300.000+

**facebook** 
(Anzahl follower)
1 = 1-499
2 = 500-4999
3 = 5000-19.999
4 = 20.000-99.999
5 = 100.000-299.999
6 = 300.000+

**youtube** 
(Anzahl Abonnenten)
1 = 1-499
2 = 500-4999
3 = 5000-19.999
4 = 20.000-99.999
5 = 100.000-299.999
6 = 300.000+

# EDGE-Attribute

**from**
(id)

**to**
(id)

**relationship**
1 = Ministerium (auch angegliedert als Staatsekretär:in)
2 = politische Funktionen
3 = Ehrenamt
4 = Unternehmen und Aufsichtsräte
5 = Stipendien
6 = Berufstätigkeiten
7 = Studienort in In- und Ausland

**year** 
(Bezieht sich auf das Jahr, in dem die Variable relationship erhoben wurde)

##
