Tools to integrate the odd-importer, -transformer, -exporter and -scheduler. The respective docker images of each of these components need to be built first in order for the _docker-compose.yml_ to work. Adjust the names of the images according to how you named the docker-images of the respective components. The _.env-file_ is used by the scheduler. This exemplary configuration assumes _two_ exporters, directed at _two different_ dashboard-databases and associated with _two separate_ Pilots (_Amsterdam Swapshop_ and _Milano Foody Zero Waste_), to be deployed. Please adjust both files according to your individual configuration. The paths to the respective database-endpoints have to be added.


# installation guide

- docker-compose up