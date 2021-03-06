# Android Projects for [Udacity Android Developer](https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801)
Built mobile apps  
* [Naturalist Hike Assistant](#capstone) (My capstone project)
* [Weather 4 WatchFace](#watchface) (App for Android Watch Face)
* [XZY Reader](#xyzreader) (Material Design)
* [Build It Bigger](#builditbig) (App commercialization)
* [Stock Hawk](#stockhawk) (Turn a Crashing App into a Product)
* [Movie Fun](#movieapp) (App for Android phone and tablet) 

<a id="capstone"></a>
### [Naturalist Hikers Assistant](https://github.com/mingrutar/Capstone-Project)
<b>Naturalist Hikers Assistant</b> helps hikers prepare for the hike, assists hikers during hiking and helps hikers reviewing their observation. However, the capstone project focuses on pre-trip preparation. See details of capstone project in the document.

|  |  |  |  |  |
|:-----|:-----|:-----|:-----|:-----|
| ![](images/setup_my_location.png) | ![](images/current_trip.png) | ![](images/trip_detail.png) | ![](images/plant_list.png) | ![](images/meetat_user_defined.png) |
| Setup my location | The home page<br> shows the upcoming trip | The trip details | The plants I am interested<br>to see at this trip | The meet up places |
| ![](images/plant_detail_fav.png) | ![](images/plant_list_on_hike.png) | ![](images/future_trip.png) |![](images/weather.png) | ![](images/widget_1.png) |
| A detail description<br> about a plant | During the hike, I <br>can mark the plant <br>when I saw it and take <br>photos if I like | The list of future trips | The weather report of<br>the hiking day | App widget |

<a id="watchface"></a>
### [Weather 4 WatchFace](https://github.com/mingrutar/WatchFace)
Android watch face app that shows weather info. The watch face couples with Sunshine phone app. Features:
* The background color of watch face could be changed at app. 
* The temperature could be displayed in metric or imperial. 
* The Sunshine app fetches weather info periodically and update the watch after sync. 
* The display of watch face has normal, ambient and low-energy modes, see screenshots. 
* Tapping watch face 2 times launches Sunshine app at phone.

|  |  |  |  |  |
|:-----:|:-----:|:-----:|:-----:|:-----:|
| ![](images/green_clear.png) | ![](images/blue_snow.png) | ![](images/ambient.png) | ![](images/save_mode.png) | ![](images/no_weatherInfo.png) |
| connected to phone<br>*round face* | blue background<br>*round face* | ambient mode<br>*round face* | save mode<br>*square face* | no weather info<br>*square face* |

<a id="xyzreader"></a>
### [XYZ Reader](https://github.com/mingrutar/MyXYZReader)
Redesign the app UI to comply with material design. The comparison of before and after redesign (not able to show the added material design style animations)

__The Original App Screens__

|  |  |
|:-----:|:-----:|
| ![](images/v0-portrait.png) | ![](images/v0-portrait-detail.png) |

__My Material Design App Screens__

| Views | Portait | Landscape |
|:-----:|:-----:|:-----:|
| Catalog | ![](images/v1-portrait.png) | ![](images/v1-landscape-1.png) |
| Detail | ![](images/v2-portait-details.png) | ![](images/v2-landscape-detail.png) |
| Full Image | ![](images/v1-portrait-largeImage.png) | ![](images/v2-lanscape-largeimage.png) |

<a id="builditbig"></a>
### [Build It Bigger](https://github.com/mingrutar/BuildItBigger)
Learn how to add aDworks in Android app:
* Free and paid versions
* Google banner image ads and interstitial image ads

The app fetches a joke from GCE, which randomly selects a joke from a joke list. If the app failed to obtain a joke from GCE, it asks a joke from a java library included in the project.

<a id="stockhawk"></a>
## [Stock Hawk](https://github.com/mingrutar/stockHawk)
The project starts with base code that is not production ready: limited function, occasional crash, etc. Improvements:
* Added a detail fragment that contains stock history in a graphic plot. The detail fragment is attached on top of main activity.
* The fab button alternate between add, for adding stock, and collapsing for remove detail fragment.
* Added collapsible toolbar with an image beautifies the app.
* The UI design follows material design principles.
* Added widget.
* Added Right to Left capability for internationalization
* Improved accessibility.
* Redesign all UI, including logo and widget.
* Fixed bugs and tighten up the app for production

Screen comparison of before and after:

__The Original App Screens__

|  |  |
|:-----:|:-----:|
| ![](images/v0-portrait_sh.png) | ![](images/v0-landscape.png) |

__My Re-implemented App Screens__

|  |  |  |  |
|:-----:|:-----:|:-----:|:-----:|
| ![](images/v2-portrait.png) | ![](images/v2-portrait-detail.png) | ![](images/dialog.png) | ![](images/RtoL.png) |
| Portait Normal<br>"+" for add | Portait Detail | Add Stock Dialog | in Arabic |
| ![](images/v2-landscape.png) | ![](images/v2-landscape-detail_sh.png) | ![](images/v2-landscape-detail2.png) | ![](images/widgets.png) |
| Landscape Normal | Landscape Detail | Stock History Range | Widget |

<a id="movieapp"></a>
## [Movie Fun](https://github.com/mingrutar/movieApp)
Created the app from scratch. Utilize Android components: RecyclerView, ContentProvider, SyncAdapter and more. Support various android device screen sizes and orientations.  

### Screenshots ###

__Tablet (1 screen 2 panes)__

| Landscape   | Portrait  |
|:---:|:---:|
| ![](images/P2-tablet-land.png) | ![](images/P2-tablet-port-favor.png) |

__Phone (1 pane 2 screens)__

| Orientation | Screen 1  | Screen 2  |
|---:|:---:|:---:|
| Portrait | ![port-main](images/P2-main-port.png) | ![port-detail-favorite](images/P2-detail-port-favor.png) |
| Landscape | ![land-main](images/P2-main-land.png) | ![land-detail](images/P2-detail-land.png) |
