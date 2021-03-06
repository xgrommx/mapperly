# Mapperly

Mapperly is a simple + interactive map of the New York City subway. 

Built using d3.js and served with the Play framework. The project is hosted on Heroku.

![Mapperly](https://raw.github.com/daveswartz/mapperly/master/mapperly.png)

## Getting Started

* Install Play 2.1.3 following the instructions in the [Play framework documentation](http://www.playframework.com/documentation/2.1.3/Installing);
* In the project root run: `play run`;
* Navigate to [http://localhost:9000](http://localhost:9000) in your web browser.

## Data

* `assets/data/paths.json` -- GeoJson file that stores the path of each subway line.
* `assets/data/stops.json` -- GeoJson file that stores the location and name of each subway stop.
* `assets/data/transfers.json` -- GeoJson file that stores the location and name of each subway transfer.

## Copyright and license

Copyright 2012 David Swartz

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.