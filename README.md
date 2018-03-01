![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)

# Warsztaty - Docker Swarm
Repozytorium plików do jedniodniowego warsztatu Docker Swarm.

## Dla kogo?

Szkolenie skierowane jest do programistów jak i administratorów chcących poznać zasadę działania platformy orkiestrującej ekosystem kontenerów na podstawie środowiska Docker Swarm.

## Co oferujemy?

Szkolenie porusza zagadnienia związane z wymaganiami stawianymi przed platformami orkiestracyjnymi wraz z ich realizacją na przykładzie środowiska Docker Swarm. Omawiana jest wysoka dostępność usług (High Availability – HA) oraz automatyzacja i load-balancing wraz z autodiscoveringiem i autorejestracją usług.

Wymagana jest wiedza związana z platformą Docker oraz systemami Linux/Unix. Uczestnik musi posiadać również elementarną wiedzę na temat sieci TCP/IP.

## Agenda

1.	Wstęp do orkiestracji
2.	Uruchominie klastra w Swarm Mode
    * [01 - Połączenie](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/01-Polaczenie)
    * [02 - Przygotowanie klastra](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/02-Przygotowanie-klastra)
    * [03 - Serwisy i taski](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/03-Serwisy-i-taski)
    * [04 - Manomarks](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/04-Manomarks)
3.	Ingress Routing, porty i Loadbalancing
    * [05 - Ingress i Host Network](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/05-Ingress-i-Host-Network)
    * [06 - Service-discovery](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/06-Service-discovery)
4. Pożądany stan serwisu
    * [07 - Constraints](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/07-Constraints)
    * [08 - Zmiany w klastrze](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/08-Zmiany-w-klastrze)
5. Przeprowadzanie Updatów serwisu
    * [09 - Update](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/09-Update)
6. Sieć pomiędzy kontenerami
    * [10 - Overlay](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/10-Overlay)
7. Uruchamianie przy pomocy Stacków
    * [11 - Stack](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/11-Stack)
8. Health Check i Limity
    * [12 - Health check](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/12-Health-check)
    * [13 - Limity zasobów](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/13-Limity-zasobow)
9. Zabezpieczenie Secrets
    * [14 - Secrets](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/14-Secrets)
10. Portainer i Rancher
    * [15 - Portainer](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/15-Portainer)
    * [16 - Rancher](https://github.com/inleo-pl/Warsztaty-Docker-Swarm/blob/master/16-Rancher)

## Kiedy, co i jak?

Najbliższy możliwy termin i prowadzący podany jest po zebraniu grupy. Warsztaty potwierdzimy tydzień przed terminem. Jeżeli z jakiegoś powodu się one nie wydarzą, co zdarza się niezmiernie rzadko, to dostaniesz zwrot kosztów lub możliwość wzięcia udziału w kolejnym terminie. Zajęcia trwają 8h wraz z przerwą.

Warsztaty będą odbywać się w maksymalnie pięcio osobowym (wraz z prowadzącym) składzie w Warszawie. Podczas zajęć nie pozwolimy ci umrzeć z głodu – będzie ciągła przerwa kawowa (kawa/herbata/ciacha), oraz w połowie dnia obiad. Na koniec wydajemy silky smooth certyfikat ukończenia z Twoim imieniem i nazwiskiem, potwierdzający udział w warsztatach. Zapraszamy!

Więcej informacji znjadziesz tutaj: https://inleo.pl/produkt/docker-swarm/.

## Źródła i przydatne linki

 * https://sysadmins.co.za/setup-a-3-node-docker-swarm-on-ubuntu-16/
 * http://docker-k8s-lab.readthedocs.io/en/latest/docker/docker-swarm.html
 * https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/
 * https://docs.docker.com/engine/swarm/swarm-tutorial/add-nodes/
 * https://github.com/dockersamples/docker-swarm-visualizer
 * https://docs.docker.com/engine/swarm/swarm-tutorial/drain-node/
 * https://docs.docker.com/engine/swarm/swarm-tutorial/rolling-update/
 * https://docs.docker.com/engine/swarm/swarm-tutorial/delete-service/
 * https://docs.docker.com/engine/swarm/swarm-tutorial/scale-service/
 * https://docs.docker.com/engine/swarm/swarm-tutorial/inspect-service/
 * https://docs.docker.com/engine/swarm/swarm-tutorial/deploy-service/
 * https://github.com/google/cadvisor
 * https://github.com/docker/swarmkit
 * https://docs.docker.com/compose/compose-file/
 * https://github.com/g0t4/docker-swarm-mode-getting-started/tree/master/services
