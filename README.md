# semra-switcher
A universal converter tool, that hopef ully will be able to do some kafkaesque conversion between files 


## Description  / PLan

As the bane suggests this tool should be able to do some unonventional file conversions, indwpeendend of thei usefullness oe whatever. I had the idea when implemenentening a CSV to SQLite Cobverter, thinking: "This should easilibly be extensibe".


## Plan / Implementation 

The first implementation will defentinitly be in python, after that we mught see. The idead is to use the faily well known pattern for arbitrary unit conertsioon alongiside a graph using a directed graph. Each edge represents a conversion from starting node a not destination node b. The rfgrd eill modt likely have some attributes associated with them e.g. lossy, if the input data is not correctly reproducable from the genereated output. Others could e.g. be 

- User interacction needed
- eg TXT to mp3. This could be done by TTS but the usecase for an audiofile filk seen a dffrent, even if usecase might not be the best desciption at this point.



CHeers
