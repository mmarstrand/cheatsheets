# Shell Commands 

## Command line by Codeacademy

+   **The command line** is a text interface for the computer’s operating system. To access the command line, we use the terminal.

*   A **filesystem** organizes a computer’s files and directories into a tree structure. It starts with the root directory. Each parent directory can contain more child directories and files.
From the command line, you can navigate through files and folders on your computer:

*   **`pwd`** = print working directory. Outputs the name of the current working directory.

*   **`ls`** = list. Lists all files and directories in the working directory.

*   **`cd`** = change directory. Switches you into the directory you specify.

    *    `..` Weiterleitung in übergeordnete Ordner. To move up one directory, use cd ... Here, cd .. navigates up from jan/memory/ to jan/

*   **`mkdir`** make / create a new directory (eg. folder) in the working directory.

    * **`mkdir -p`** [Ordner/Unterordner/Unterunterordner/...] create new subfolder in directory

* **`touch`** [Dateiname] create a new file inside the working directory.

- `tree` Verzeichnisbaum anzeigen
- `curl` lädt Objekt über eine URL
- `cat` zeigt den Inhalt einer Datei


### Options modify the behavior of commands:

*   **`ls -a`** lists **a**ll contents of a directory, including hidden files and directories

*   **`ls -l`** lists all contents in long format

*   **`ls -la`** Liste mit Details `l` (=long; untereinander auflisten) und durch `a` (=all) werden

*   **`ls -t`** orders files and directories by the time they were last modified

*   Multiple options can be used together, like `ls -alt` (all, long, time combined)

### Copy, move, and remove files and directories:

* **`cp`** copies files
* **`mv`** = moves and renames files
  - ex. `mv [alter Name] [neuer Name]` Ordner/Datei umbenennen
  - ex.`mv [alter Pfad] [neuer Pfad]` Ordner/Datei verschieben
  - ex. `mv [Ordner] *` verschieben des Ordners in den aktuellen Ordner

* **`rm`** remove files
  - **`rm -r`** remove directories / folder
  - `rm -rf` Ordner löschen; `r` = rekursiv (alles in allen Unterordnern); `f` = force (nicht jede Datei einzeln bestätigen); auch **Rimraf** genannt
  - `rm -rf *` löschen aller Ordner und Dateien im aktuellen Ordner

-  `*` Wildcards are useful for selecting groups of files and directories

- `code .` aktueller Ordner wird bei Visual Studio Code aufgerufen
- `open [Datei]` öffnet Datei mit dem Standardprogramm eines Betriebssystems
- `open .` öffnet Ordner im Finder/Explorer
______


# Jan's Cheat Sheet für **Shell Befehle**

#### Wechseln zu anderen Ordnern / Inhalt anzeigen etc.:

- `cd [Ordnername]` change directory
- `..` Weiterleitung in übergeordnete Ordner
- `z neu` = `cd ~/neuefische` z lernt oft benutzte Ordner und bietet so Abkürzung
- `ls` Liste aller Dateien und Unterordner eines Ordners
- `ls -la` Liste mit Details `l` (=long; untereinander auflisten) und durch `a` (=all) werden auch versteckte Dateien angezeigt
- `tree` Verzeichnisbaum anzeigen
- `curl` lädt Objekt über eine URL
- `cat` zeigt den Inhalt einer Datei

#### Neu, verschieben, kopieren, löschen, öffnen:

- `mkdir` Ordner erstellen
- `mkdir [Ordner/Unterordner]` Unterordner erstellen
- `mkdir -p [Ordner/Unterordner/Unterunterordner/...]` Ordnerpfad wird erzeugt
- `touch [Dateiname]` Datei erstellen
- `mv [alter Name] [neuer Name]` Ordner/Datei umbenennen
- `mv [alter Pfad] [neuer Pfad]` Ordner/Datei verschieben
- `mv [Ordner] *` verschieben des Ordners in den aktuellen Ordner
- `cp -R [src-directory] [target-directory]` kopiert alles aus dem Quellverzeichnis in das Zielverzeichnis
- `pbcopy` speichert Eingabe in die Zwischenablage (Bsp.: `cat ~/.ssh/id_rsa.pub | pbcopy`)
- `rm` remove (geht nur bei Dateien)
- `rm -rf` Ordner löschen; `r` = rekursiv (alles in allen Unterordnern); `f` = force (nicht jede Datei einzeln bestätigen); uch **Rimraf** genannt
- `rm -rf *` löschen aller Ordner und Dateien im aktuellen Ordner
- `code .` aktueller Ordner wird bei VS Code aufgerufen
- `open [Datei]` öffnet Datei mit dem Standardprogramm eines Betriebssystems
- `open .` öffnet Ordner im Finder/Explorer

test new change
