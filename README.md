Datenbank-Deutschland
=====================

Ort, Kreis, Bundesland, PLZ, GeoCode von Orten in Deutschland




Die Datenbank
=====================

--
-- Tabellenstruktur für Tabelle `Dcitys`
--

CREATE TABLE IF NOT EXISTS `Dcitys` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `bundesland` varchar(30) DEFAULT NULL,
  `kreis` varchar(35) DEFAULT NULL,
  `stadt` varchar(30) DEFAULT NULL,
  `stadtteil` varchar(30) DEFAULT NULL,
  `recht` varchar(6) DEFAULT NULL,
  `lat` float DEFAULT NULL,
  `lon` float DEFAULT NULL,
  `plz` int(5) unsigned zerofill NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM  DEFAULT CHARSET=latin1 COMMENT='Deutsche Städte' AUTO_INCREMENT=11369 ;



Die Daten

Wenn die Tabelle angelegt wurde importiere die data.sql

