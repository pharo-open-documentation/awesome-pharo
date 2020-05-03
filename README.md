# Awesome Pharo [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A categorized community-driven collection of awesome Pharo libraries, tools, frameworks and software.

## Table of contents

- [Algorithms](#algorithms)
- [Artificial Intelligence and Machine Learning](#artificial-intelligence-and-machine-learning)
- [Books](#books)
- [Code generation](#code-generation)
- [Code quality](#code-quality)
- [Command line](#command-line)
- [Data interexchange format](#data-interexchange-format)
- [Data structures](#data-structures)
- [Databases](#databases)
- [Datasets](#datasets)
- [Documents generation](#documents-generation)
- [Graphics](#graphics)
- [IDE](#ide)
- [Interaction](#interaction)
- [IOT](#iot)
- [Language extensions](#language-extensions)
- [LaTeX](#latex)
- [Loggers](#loggers)
- [Meta-modelling](#meta-modelling)
- [Miscellaneous](#miscellaneous)
- [Network protocols](#network-protocols)
- [Pharo images management](#pharo-images-management)
- [Projects management](#projects-management)
- [Scientific libraries](#scientific-libraries)
- [Software / data analysis](#software--data-analysis)
- [Sound](#sound)
- [System interaction](#system-interaction)
- [Testing](#testing)
- [Tutorials](#tutorials)
- [VCS](#vcs)
- [Videos](#videos)
- [Web](#web)
- [Web API clients](#web-api-clients)

## Algorithms
+ [DeepTraverser](https://github.com/pharo-contributions/DeepTraverser) - Library for traversing object graphs (managing cycles).
+ [FuzzySearcher](https://github.com/hernanmd/FuzzySearcher) - Simplified implementation of ambiguous matching algorithm based on Baeta-Yates, R.A., Gonnet, G.H., Wu, S. and Manber, U.
+ [StableMarriage](https://github.com/juliendelplanque/StableMarriage) - A solver for the stable marriage problem written in Pharo.

## Artificial Intelligence and Machine Learning

The full list of AI and machine learning libraries, tools, and resources for Pharo is available at [pharo-ai / awesome-pharo-ml](https://github.com/pharo-ai/awesome-pharo-ml).

+ [Keras Wrapper](https://github.com/ObjectProfile/KerasWrapper) - Allows to use [Keras](https://keras.io/) functions within Pharo.
+ [NEAT (NeuroEvolution of Augmenting Topologies)](https://github.com/bergel/NEAT) - A genetic algorithm for evolving artificial neural networks. NEAT is probably the most popular algorithm for neuroevolution.
+ [pharo-ai / APriori](https://github.com/pharo-ai/APriori) - Fast algorithm for mining frequent sets of items and finding association rules between items in a database of transactions.
+ [pharo-ai / KMeans](https://github.com/pharo-ai/KMeans) - K-means clustering.
+ [pharo-ai / NaiveBayesClassifier](https://github.com/pharo-ai/NaiveBayesClassifier) - Implementation of a multinomial Naive Bayes classifier in Pharo that can be used for simple spam detection and sentiment analysis.
+ [pharo-ai / NgramModel](https://github.com/pharo-ai/NgramModel) - N-gram language model that can be trained to estimate the probability of a next word based on N-1 previous words.
+ [pharo-ai / TF-IDF](https://github.com/pharo-ai/TF-IDF) - Term Frequency - Inverse Document Frequency (TF-IDF), a statistical metric that reflects the importance of a word in a document. Can be used for finding keywords, ranking words by importance, or as a simple way of finding semantic similarity between documents.
+ [TensorFlow Bindings](https://github.com/PolyMathOrg/libtensorflow-pharo-bindings) - Allows to use [TensorFlow](https://www.tensorflow.org/) in Pharo.

## Books
+ [https://books.pharo.org](https://books.pharo.org) - Pharo books are a collection of technical or textbook books around Pharo. 
+ [Agile Artificial Intelligence](https://agileartificialintelligence.github.io) - Agile Artificial Intelligence is a book that covers classical algorithms commonly assimilated as artificial intelligence techniques.
+ [Agile Visualization](http://agilevisualization.com) - Visualization made easy in Pharo. It uses the Roassal visualization engine
+ [Free online books from Stéphane Ducasse website](http://stephane.ducasse.free.fr/FreeBooks.html) - A collection of free books related to Smalltalk and Pharo.
+ [SquareBracketAssociates](https://github.com/SquareBracketAssociates) - Organisation grouping repositories for various books around Pharo.

## Code generation
+ [PharoJS](https://github.com/bouraqadi/PharoJS) - Converts Pharo code to Javascript.
+ [Python3Generator](https://github.com/juliendelplanque/Python3Generator) - A toolkit to generate Python 3 source code from Pharo.
+ [XML-XMLWriter](https://github.com/pharo-contributions/XML-XMLWriter) - Block-based API for XML generation for Pharo.

## Code quality
+ [Chanel](https://github.com/jecisc/Chanel) - A cleaner for Pharo Smalltalk code.
+ [QualityAssistant](https://github.com/Uko/QualityAssistant) - A live feedback code quality tool for Pharo.
+ [Rules](https://github.com/jecisc/Rules) - Rules is a small model of rules that a model should not violate. It is able to compute the technical debt for a set of violations.

## Command line
+ [clap-st](https://github.com/cdlm/clap-st) - Command-line argument parsing for Pharo.
+ [Pharo server tools](https://github.com/svenvc/pharo-server-tools) - Tools to deploy and manage headless Pharo servers from the command line.
+ [pi](https://github.com/hernanmd/pi) - CLI tool to install Pharo Smalltalk packages.

## Data interexchange format
+ [Arff](https://github.com/juliendelplanque/Arff) - An Arff generator written in Pharo, Arff is the dataformat used by weka.
+ [CSV](https://github.com/svenvc/NeoCSV) - NeoCSV is an elegant and efficient standalone Smalltalk framework to read and write CSV converting to or from Smalltalk objects.
+ [Fuel](https://github.com/theseion/Fuel) - A general-purpose object serialization framework for Squeak and Pharo, developed in Pharo.
+ [msgpack-smalltalk](https://github.com/msgpack/msgpack-smalltalk) - MessagePack serialization library.
+ [NeoJSON](https://github.com/svenvc/NeoJSON) - Framework to handle JSON in Pharo.
+ [NeoUniversalBinaryJSON](https://github.com/svenvc/NeoUniversalBinaryJSON) - An implementation of [Universal Binary JSON](http://ubjson.org) (UBJSON) for Pharo.
+ [pharo-ical](https://github.com/juliendelplanque/pharo-ical) - iCalendar import and export.
+ [Pillar](https://github.com/pillar-markup/pillar) - Markup syntax and associated tools to write and generate documentation, books and slides.
+ [Protobuf](https://github.com/jvdsandt/protobuf-smalltalk) - [Google's protocol buffers](https://developers.google.com/protocol-buffers/) support for Pharo Smalltalk.
+ [SIXX](https://github.com/mumez/SIXX) - XML serializer/deserializer.
+ [STON](https://github.com/svenvc/ston) - The Smalltalk Object Notation, similar to JSON but for Smalltalk.
+ [Tabular](https://github.com/VincentBlondeau/Tabular) - Support of common spreadsheets formats (CSV, XLSX, ODS).
+ [XML-Pastell](https://github.com/pharo-contributions/XML-Pastell) - An XPath-like DSL that makes navigation in XML DOM trees easier.
+ [XML-Parser](https://github.com/pharo-contributions/XML-XMLParser) - Official XML parser maintained by Pharo community.
+ [XML-Support](https://github.com/svenvc/XML-Support-Pharo) - XML Support for Pharo.
+ [XML-XMLParserStAX](https://github.com/pharo-contributions/XML-XMLParserStAX) - Official XML pull parser for XMLParser maintained by Pharo community.
+ [XML-XMLParserHTML](https://github.com/pharo-contributions/XML-XMLParserHTML) - Official parsers for HTML that convert possibly malformed HTML into well-formed XML maintained by Pharo community.
+ [XML-XMLWriter](XML-XMLWriter) - Official XML generation framework maintained by Pharo community.
+ [XML-XPath](https://github.com/pharo-contributions/XML-XPath) - Official XPath library for Pharo.
+ [Soup](https://github.com/Ducasse/Soup) - HTML Scraping library for Pharo.

## Data Structures
+ [DataFrame](https://github.com/PolyMathOrg/DataFrame) - Tabular data structures for data analysis.
+ [Dictionary with lookup](https://github.com/Ducasse/Containers-PropertyEnvironment) - A dictionary with lookup.
+ [Grid](https://github.com/Ducasse/Containers-Grid) - A grid implementation.
+ [Iterators](https://github.com/juliendelplanque/Iterators) - Implementation of the iterator design pattern.
+ [Multimap](https://github.com/Ducasse/Containers-OrderedMultiMap) - A multi map implementation.
+ [OrderPreservingDictionary](https://github.com/Ducasse/Containers-OrderPreservingDictionary) - Order preserving dictionary.
+ [OrderedSet](https://github.com/olekscode/Containers-OrderedSet) - A Set where an order of elements matters or an OrderedCollection with no duplicates. Supports the complete API of Set and OrderedCollection.
+ [PropertyEnvironment](https://github.com/Ducasse/Containers-PropertyEnvironment) - A dictionary of properties with a lookup in ancestors (also called environment in other languages).
+ [Stack implementation](https://github.com/Ducasse/Containers-Stack) - A stack implementation.
+ [UniqueOrdered collection](https://github.com/Ducasse/Containers-UniqueOrdered) - Some collection to have unique ordered elements. 

## Databases
+ [CDB](https://github.com/Ducasse/CDB) - a CDB implementation in Pharo. 
+ [CouchDB](https://github.com/eMaringolo/pharo-couchdb) - Pharo client for CouchDB NoSQL Document Database.
+ [Garage](https://github.com/pharo-rdbms/garage) - Database drivers for the Pharo language.
+ [Glorp](https://github.com/pharo-rdbms/glorp) - Multi-database cross-platform object-relational persistence for Pharo and many other Smalltalks.
+ [GlorpSQLite](https://github.com/PierceNg/glorp-sqlite3) - SQLite for Pharo, standalone and integrated with Glorp.
+ [P3](https://github.com/svenvc/P3) - PostgresV3 protocol client for Pharo, standalone and integrated with Glorp.
+ [pharo-ado](https://github.com/eftomi/pharo-ado) - Enable data persistence in Pharo by using ActiveX Data Objects (ADO) on Microsoft Windows and external DBMS.
+ [Pharo-UDBC](https://github.com/astares/Pharo-UDBC) - Pharo Universal Database Connectivity.
+ [PunQLite](https://github.com/mumez/PunQLite) - UnQLite binding for Pharo Smalltalk.
+ [Tarantalk](https://github.com/mumez/Tarantalk) - Tarantool client for Pharo.
+ [SCouchDB](https://github.com/jmari/SCouchDB) - Pharo driver for CouchDB database using Zinc client. Supports Mango queries and implements Voyage API.
+ [SQLite3](https://github.com/juliendelplanque/SQLite3) - A clean SQLite FFI binding for Pharo for those who only want to use SQLite easily.
+ [Voyage](https://github.com/pharo-nosql/voyage) - An object persistence abstraction layer for Pharo.

## Datasets
+ [Datasets](https://github.com/pharo-ai/Datasets) - A collection of small toy datasets used for demonstration and experiments with AI and machine learning. Includes many famous datasets such as Iris, Boston Housing, Wine, Diabetes, MNIST, etc.
+ [Les Miserables](https://github.com/bergel/LesMiserables) - Coappearance characters of Les Miserables.
+ [RandomPartitioner](https://github.com/pharo-ai/RandomPartitioner) - A tool for partitioning a dataset. Given a set of proportions (e.g. 50%, 30%, and 20%), it shuffles the collection and divides it into non-empty subsets in such a way that every element is included in exactly one subset. Can be used in machine learning and statistical analysis for splitting datasets into training, validation, and test sets.

## Documents Generation
+ [Artefact](https://github.com/pharo-contributions/Artefact) - Artefact is a framework to generate PDF documents in Pharo.

## Graphics
+ [Bloc](https://github.com/pharo-graphics/Bloc) - Next generation low-level UI infratructure and framework for Pharo.
+ [Brick](https://github.com/pharo-graphics/Brick) - Next generation widget libraries for Pharo. Works on top of Bloc.
+ [ConstraintsLayout](https://github.com/tesonep/ConstraintsLayout) - A constraints layout for morphic using Cassowary as its backend.
+ [Colors Extensions](https://github.com/pharo-contributions/ColorsExtensions) - Extensions to Pharo colors.
+ [GraphViz](https://github.com/hernanmd/GraphViz) - Pharo GraphViz binding.
+ [Jun](https://github.com/tomooda/Jun) - A 3D graphics library with chemoinformatics extensions.
+ [MaterialColors](https://github.com/DuneSt/MaterialColors) - Project implementing Material Design recommandations on colors.
+ [PlantUMLPharoGizmo](https://github.com/fuhrmanator/PlantUMLPharoGizmo) - Pharo support for PlantUML.
+ [Roassal](https://github.com/ObjectProfile/Roassal2) - The agile 2D visualization engine for Pharo.
+ [Sparta](https://github.com/syrel/Sparta) - Sparta is an almost stateless vector graphics API for Pharo that provides bindings to the Moz2D rendering backend. 
+ [SpecUIAddOns](https://github.com/hernanmd/SpecUIAddOns) - Add-ons for Spec UI description framework.
+ [Woden](https://github.com/ronsaldo/woden) - A 3D graphics engine for Pharo.

## IDE
+ [Calypso](https://github.com/pharo-ide/Calypso) - Pharo system browser.
+ [CollectionExtensions](https://github.com/pharo-contributions/CollectionExtensions) - Extensions for Pharo collections API.
+ [Dawn theme](https://github.com/sebastianconcept/PharoDawnTheme) - A warm dark theme for Pharo.
+ [Glamorous Toolkit](https://github.com/feenkcom/gtoolkit) - Moldable IDE for Pharo.
+ [Mirage](https://github.com/juliendelplanque/Mirage) - A windows switcher with a previewer for Pharo.
+ [Native-Browser](https://github.com/jecisc/Native-Browser) - A small project to add the possibility to open native browser via a FileReference.
+ [Smalltalk Vim Mode](https://github.com/unchartedworks/SmalltalkVimMode) - Vim Mode for Playground, System Browser, Debugger in Pharo.
+ [TelePharo](https://github.com/pharo-ide/TelePharo) - Tools to manage and develop remote Pharo images.
+ [TilingWindowManager](https://github.com/Pharophile/TilingWindowManager) - Tiling Window Manager for Pharo.

## Interaction
+ [GitBridge](https://github.com/jecisc/GitBridge) - Access resources and information from the git repository containing your project.
+ [OSC](https://github.com/Ducasse/OSC) - An open sound control library.
+ [TUIO](https://github.com/Ducasse/TUIO) - A driver for TUIO.

## IOT
+ [HID](https://github.com/tamerescrl/libusb-pharo#hid-layer) - An implementation of the Human Interface Device protocol with a driver to be used with libusb.
+ [PharoThings](https://github.com/pharo-iot/PharoThings) - Live programming platform for IoT projects based on Pharo.

## Language extensions
+ [I18N](https://github.com/astares/Pharo-I18N) - Internationalization support for applications.
+ [Talents](https://github.com/tesonep/pharo-talents) - Implementation of Talents in Pharo. Allowing us to extend the behaviour in single instances.

## LaTeX
+ [Citezen](https://github.com/Ducasse/Citezen) - A bibtext parser and tool suite.
+ [SmalltalkEnv](https://github.com/mattonem/SmalltalkEnv) - LaTeX environment for Smalltalk.

## Loggers
+ [Beacon](https://github.com/noha/pharo-beacon) - A logger using beacon.
+ [TinyLogger](https://github.com/jecisc/TinyLogger) - A really small logger for Pharo applications.

## Meta-modelling
+ [Magritte](https://github.com/magritte-metamodel/magritte) - A fully dynamic meta-description framework.

## Miscellaneous
+ [Aconcagua](https://github.com/ba-st/aconcagua) - This model represents measures as first class objects, that is, an object that encapsulates a number with its unit.
+ [BugReport](https://github.com/jecisc/BugReport) - A small project to ease the bug reporting in Pharo application by dumping clear and detailed stacks. 
+ [DMirror](https://github.com/ObjectProfile/DMirror) - Tool to spawn new job on forked Pharo images.
+ [Dr Geo](http://www.drgeo.eu/home) - A software to design & manipulate interactive geometric sketches. It helps kids to explore geometry.
+ [Fog](https://github.com/smartanvil/Fog) - Pharo Ethereum Driver.
+ [IPFS](https://github.com/khinsen/ipfs-pharo) - Binding to InterPlanetary File System for Pharo.
+ [ISO3166](https://github.com/hernanmd/ISO3166) - Codes for the names of countries, dependent territories, and special areas of geographical interest for Pharo applications.
+ [PharoFamily](https://files.pharo.org/media/pharo-family1.pdf) - PDF image showing a part of Pharo ecosystem.
+ [PharoMisc](https://github.com/bouraqadi/PharoMisc) - Small utilities and libraries around various topics.
+ [PTerm](https://github.com/lxsang/PTerm) - Using Unix terminal from Pharo.
+ [Stylesheet](https://github.com/pharo-contributions/Stylesheet) - Stylesheet is a project to define css like stylesheet in Pharo applications.
+ [Territorial](https://github.com/hernanmd/Territorial) - Geographical Information Retrieval (GIR) project including features to access geopolitical objects like Nations, Cities, Regions, International Organizations, and statistical data.

## Network protocols
+ [FileSystemNetwork](http://smalltalkhub.com/#!/~UdoSchneider/FileSystemNetwork) - Adds WebDAV and FTP support to Pharo's FileSystem framework. This allows you to use remote WebDAV and FTP locations with the same (FileSystem) API that's used for disk access.
+ [JRPC](https://github.com/juliendelplanque/JRPC) - Yet another [JSON-RPC 2.0](https://www.jsonrpc.org/specification) implementation for Pharo Smalltalk.
+ [Zodiac](https://github.com/svenvc/zodiac) (built-in) - Zodiac is an open-source Smalltalk framework implementing TLS/SSL secure as well as regular socket streams.

## Pharo images management
+ [fari.sh](https://github.com/cdlm/fari.sh) - Fresh, ready-to-hack Pharo images.
+ [Pharo Install](https://github.com/hernanmd/pi) - A command-line tool for installing Pharo Smalltalk packages into fresh images.
+ [Pharo Launcher](https://github.com/pharo-project/pharo-launcher) - Official tool to manage your pharo images and download new ones.

## Projects management
+ [Chrysal](https://github.com/Ducasse/Chrysal) - How to manage application configuration. 
+ [Cruiser](https://github.com/VincentBlondeau/Cruiser) - Application packager for Pharo.
+ [DeploymentUtility](https://github.com/jecisc/DeploymentUtility) - A project providing a facade to help to deploy pharo projects. 
+ [Filetree](https://github.com/dalehenrich/filetree) - A file-per-method export format of Pharo source code allowing one to version code with git, svn, fosil, etc.
+ [Metacello](https://github.com/Metacello/metacello) - A package management system for Pharo.
+ [pharo-server-tools](https://github.com/svenvc/pharo-server-tools) - Tools to deploy and manage headless Pharo servers from the command line.
+ [SmalltalkCI](https://github.com/hpi-swa/smalltalkCI) - Framework for testing Smalltalk projects on Linux, macOS, and Windows and on Travis CI, AppVeyor, and GitLab CI/CD.
+ [Tonel](https://github.com/pharo-vcs/tonel) - A file-per-class export format of Pharo source code allowing one to version code with git, svn, fosil, etc.

## Scientific libraries
+ [BioSmalltalk](https://github.com/hernanmd/BioSmalltalk) - Bioinformatics Library for Pharo Smalltalk.
+ [CORMAS](https://github.com/cormas/cormas) - CORMAS (Common-pool Resource and Mutli-Agent Simulation) is a agent based model library in Smalltalk.
+ [GADM](https://github.com/hernanmd/GADM) - A browseable GADM world tree for Pharo Smalltalk.
+ [Geometry](https://github.com/TelescopeSt/Geometry) - A library for representing basic geometry elements and doing computations with them.
+ [HoneyGinger](https://github.com/tomooda/HoneyGinger) - a fluid dynamics simulation engine focused on interactivity and visualization
+ [Kendrick](https://github.com/UMMISCO/kendrick) - Domain-Specific Modeling for Epidemiology.
+ [MatplotLibBridge](https://github.com/juliendelplanque/MatplotLibBridge) - A bridge to Python's Matplotlib.
+ [Polymath](https://github.com/PolyMathOrg/PolyMath) - Set of mathematical tools for Pharo. Similar to numpy in Python.
+ [RMapViewer](https://github.com/ReactionMap/RMapViewer) - A Viewer for chemical reaction maps.
+ [StNER](https://github.com/hernanmd/StNER) - Interface to the Stanford Named Entity Recognizer.
+ [Units](https://github.com/zweidenker/Units) - A simple package for Units management in Pharo.
+ [Z3950](https://github.com/hernanmd/Z3950) - ZOOM FFI Client for Z39.50 Protocol.

## Software / data analysis
+ [CCBC](https://github.com/hernanmd/ccbc) - Code Critics Bar Chart for Pharo Smalltalk.
+ [DesignInfo](https://github.com/hernanmd/DesignInfo) - Collects package metrics (SLOC).
+ [Moose](https://github.com/moosetechnology/Moose) - Platform for software and data analysis.
+ [PetitParser](https://github.com/moosetechnology/PetitParser) - Petit Parser is a framework for building parsers using objects.
+ [PostgreSQLParser](https://github.com/juliendelplanque/PostgreSQLParser) - A parser for PostgreSQL queries and Plpg/SQL source code.

## Sound
+ [Pharo-LibVLC](https://github.com/badetitou/Pharo-LibVLC) - FFI binding to [libVLC](https://www.videolan.org/developers/vlc/doc/doxygen/html/group__libvlc.html).
+ [PharoSound](https://github.com/psvensson/PharoSound) - Sound facilities for Pharo.

## System interaction
+ [KerasBridge](https://github.com/ObjectProfile/KerasBridge) - Bridge between the Keras library for neural network and Pharo
+ [LibUSB](https://github.com/tamerescrl/libusb-pharo) - A FFI binding to libusb C library.
+ [OSSubprocess](https://github.com/pharo-contributions/OSSubprocess) - Allows one to spawn Operating System processes from within Pharo language.
+ [Pharo-OS-Linux-Ubuntu](https://github.com/astares/Pharo-OS-Linux-Ubuntu) - Support for Ubuntu operating system for Pharo.
+ [Pharo-OS-OSX](https://github.com/astares/Pharo-OS-OSX) - Support for OSX operating system for Pharo.
+ [Pharo-OS-Unix](https://github.com/astares/Pharo-OS-Unix) - Support for Unix operating system for Pharo.
+ [Pharo-OS-Raspbian](https://github.com/astares/Pharo-OS-Raspbian) - Support for Raspbian operating system for Pharo.
+ [Pharo-OS-Windows](https://github.com/astares/Pharo-OS-Windows) - Support for Windows operating system for Pharo.
+ [ProcessWrapper](https://github.com/hernanmd/ProcessWrapper) - Plugin + Wrapper code for Windows process execution.
+ [PythonBridge](https://github.com/ObjectProfile/PythonBridge) - A bridge between Python and Pharo. This bridge allows to seamlessly use Python libraries in Pharo
+ [SystemInteraction](https://github.com/jecisc/SystemInteraction) - A project to simplify system interactions in Pharo providing a facade to OSSubProcess and OSWindSubProcess and some pre-made commands.

## Testing
+ [Babymock](https://github.com/zeroflag/BabyMock) - A visual mock object library.
+ [DrTests](https://github.com/juliendelplanque/DrTests/) - An extendable, plugins-based UI for testing Pharo projects.
+ [Hapao](https://github.com/ObjectProfile/Spy2) - Spy2 is a profiling framework. Spy2 contains Hapao, the visual test coverage tool.
+ [Mocketry](https://github.com/dionisiydk/Mocketry) - Mock objects library with very fluent lightweight API.
+ [µ-talk](https://github.com/pavel-krivanek/mutalk) - Mutation Testing in Smalltalk.
+ [ParametrizedTests](https://github.com/tesonep/ParametrizedTests) - Extension to SUnit to implement parametrized tests in Pharo.
+ [StateSpecs](https://github.com/dionisiydk/StateSpecs) - Assertions library based on should expressions.

## Tutorials
+ [Exercism Pharo Smalltalk](https://github.com/exercism/pharo-smalltalk) - Solve problems with TDD at [Exercism.io](https://exercism.io/) and receive mentor feedback.

## Videos
+ [How to setup a Pharo project](https://www.youtube.com/watch?v=Wnt3OBhR18I) - Video showing how to setup a Pharo project (continuous-integration setup included).
+ [Infecting morph by virus](https://www.youtube.com/watch?v=mnu51GDhOL4) - Example of usage of [Ghost](https://github.com/pharo-ide/Ghost) to infect a Morph, making it change the color of other Morphs it touches.
+ [Pharo Tech Talk Feb 2017 : Reflectivity](https://www.youtube.com/watch?v=H52MAu_ISgU) - Reflectivity in Pharo6.
+ [Pharo Techtalk: Consortium/Association 2017](https://www.youtube.com/watch?v=jYtNinyj69I) - Live stream for the pharo tech talk March 2018.
+ [Pharo TechTalk July 2019: Contribute to Pharo](https://www.youtube.com/watch?v=90T0OSb_Fuo) - TechTalk showing how to contribute to Pharo.

## VCS
+ [Iceberg](https://github.com/pharo-vcs/iceberg) - Set of tools to handle git repositories from a Pharo image.

## Web
+ [Amber](https://amber-lang.net) - Amber is an implementation of the Smalltalk language that runs on top of the JavaScript runtime. It uses Pharo as reference implementation.
+ [ChartJs](https://github.com/DuneSt/ChartJs) - Seaside binding of ChartJs to display and interact with charts.
+ [Ethel](https://github.com/grype/Ethel) - Lightweight framework for composing web service clients.
+ [HighchartsSt](https://github.com/ba-st/HighchartsSt) - A Highcharts Js API wrapper for Pharo Smalltalk.
+ [MaterialDesignLite](https://github.com/DuneSt/MaterialDesignLite) - Binding google's Material Design Lite project for Seaside.
+ [OpenAPI](https://github.com/zweidenker/OpenAPI) - A pharo implementation of [OpenAPI](https://www.openapis.org) 3.0.1, a machine-readable interface files specification for describing, producing, consuming, and visualizing RESTful web services.
+ [Parasol](https://github.com/SeasideSt/Parasol) - Testing web apps in Smalltalk using Selenium WebDriver.
+ [PharoJS](https://github.com/bouraqadi/PharoJS) - Develop in Pharo, Run on Javascript.
+ [PrismCodeDisplayer](https://github.com/DuneSt/PrismCodeDisplayer) - Code displayer for Seaside base on Prism.js project.
+ [RenoirSt](https://github.com/ba-st/RenoirSt) - A DSL enabling programmatic cascading style sheet generation for Pharo Smalltalk.
+ [Seaside](https://github.com/SeasideSt/Seaside) - Framework to develop sophisticate web applications in Smalltalk.
+ [SeasideBootstrap](https://github.com/astares/Seaside-Bootstrap) - Binding to Twitter's Bootstrap project for Seaside.
+ [Teapot](https://github.com/zeroflag/Teapot) - Micro web framework for Pharo Smalltalk.
+ [TelescopeCytoscape](https://github.com/TelescopeSt/TelescopeCytoscape) - Interactive visualization project for Seaside based on Cytoscape.js.
+ [Willow](https://github.com/ba-st/Willow) - Web Interaction Library that eases the burden of creating AJAX-based web applications.
+ [Zinc](https://github.com/svenvc/zinc) - HTTP components to deal with HTTP networking in Smalltalk.

## Web API clients
- [DiscordSt](https://github.com/JurajKubelka/DiscordSt) - DiscordSt is a client for Discord written in Pharo.
