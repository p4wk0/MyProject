dotnet run - to polecenie uruchamia aplikację .NET Core. Wykonuje ono kompilację projektu, a następnie uruchamia aplikację. Oto przykład użycia:
Powyższa komenda uruchomi aplikację w bieżącym katalogu projektu.

dotnet build - to polecenie wykonuje kompilację projektu .NET Core bez uruchamiania aplikacji. Kompilacja wygeneruje pliki wykonywalne, biblioteki i pliki wynikowe zależne od konfiguracji projektu. Oto przykład użycia:
Powyższa komenda skompiluje projekt, ale nie uruchomi go. Pliki wynikowe zostaną zapisane w katalogu bin projektu.

dotnet publish - to polecenie wykonuje kompilację projektu i publikuje wynikowe pliki wykonywalne lub biblioteki, które mogą zostać uruchomione na innych platformach. Oto przykład użycia:
dotnet publish -c Release -o output
Powyższa komenda skompiluje projekt w trybie Release i umieści wynikowe pliki w katalogu output. Dzięki temu możesz z łatwością przekazać wynikowe pliki na inne maszyny lub udostępnić je jako gotowy produkt.
