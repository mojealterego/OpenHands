# Plan audytu — OpenHands

## Status
AUDYT ZAKOŃCZONY — 2026-09-12.

## Ustalenia
Agent Canvas jest self-hosted centrum sterowania agentami kodującymi i automatyzacjami. README opisuje lokalne, Dockerowe, VM i chmurowe backendy, integracje GitHub/Slack/Linear oraz Agent Server jako osobny komponent.

## Krytyczne ryzyka
Uruchomienie bez sandboxa daje agentowi pełny dostęp do systemu plików. Wymagane są izolacja wykonania, least privilege, kontrola sekretów, separacja backendów, autoryzacja automatyzacji/webhooków oraz audyt działań agentów.

## Dalsza praca
Nie traktować ostrzeżenia o pełnym dostępie do hosta jako detalu dokumentacyjnego. Przed produkcją wymagana weryfikacja sandboxa, uprawnień, sieci, webhooków i ścieżek integracji.
