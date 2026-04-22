# Public IPTV Channels

A small, hand-curated M3U playlist of live TV channels whose streams are
served directly from the copyright holder's own infrastructure and offered
to the public free of charge. Intended as a safe built-in default for
generic IPTV players (in particular, [ColdOpen](https://coldopen.dev)).

Published at **https://iptv.coldopen.dev/channels.m3u** (GitHub Pages).

## Inclusion criteria

An entry is included **only** when all of the following are true:

1. The stream URL's hostname is operated by the channel's own publisher
   on a subdomain clearly branded to them (e.g. `live.france24.com`,
   `dwamdstream*.akamaized.net`). No generic shared Akamai / CloudFront
   edges, third-party resellers, scrapers, URL shorteners, raw-IP
   origins, or re-encoders.
2. The publisher openly distributes this feed for free public viewing on
   their own website or OTT product (linked in the provenance column
   below).
3. The stream is live-linear (continuous), not on-demand, and not locked
   behind DRM, subscription, or signed/expiring URLs.
4. Redistribution is authorized by the copyright holder. Hosts that
   merely *carry* a feed under a B2B distribution agreement (e.g. NHK
   World carried by PBS Distribution in the US, local OTA affiliates
   carried on PBS's national CDN) are excluded — the CDN holding the
   bits does not grant third-party redistribution rights.

Geographic restrictions enforced by the publisher (e.g. `[Geo-blocked]`)
are preserved as-is; the publisher's own geo-fence is what makes the
stream legitimate in its licensed territories.

## What's excluded, on purpose

- Local OTA network affiliates (Nexstar, Gray, Scripps, PBS member
  stations, etc.) — OTA carriage rights do not include internet
  streaming by a third-party app.
- FAST-only channels served through third-party ad-platforms
  (Wurl, Amagi Tubi, Samsung TV Plus, Pluto TV, etc.) unless the
  publisher themselves officially distributes that feed to those
  platforms.
- State-media propaganda outlets (CGTN, RT) — technically free but
  a poor fit for a general-audience default list.
- Feeds served from shared / generic Akamai edges (e.g.
  `*.edgesuite.net`) where the hostname is not branded to the
  publisher.

## Channels

_99 channels across 15 publishers. Last verified: 2026-04-22._

| Channel | Publisher | Provenance |
|---|---|---|
| ABC News Live 1 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 10 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 2 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 3 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 4 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 5 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 6 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 7 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 8 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| ABC News Live 9 (720p) | ABC News (The Walt Disney Company) | [link](https://abcnews.go.com/Live) |
| Al Jazeera (1080p) | Al Jazeera Media Network | [link](https://www.aljazeera.com/live/) |
| Al Jazeera Documentary (1080p) [Geo-blocked] | Al Jazeera Media Network | [link](https://www.aljazeera.com/live/) |
| Al Jazeera English (1080p) | Al Jazeera Media Network | [link](https://www.aljazeera.com/live/) |
| Al Jazeera Mubasher (1080p) | Al Jazeera Media Network | [link](https://www.aljazeera.com/live/) |
| Al Jazeera Mubasher 24 (1080p) | Al Jazeera Media Network | [link](https://www.aljazeera.com/live/) |
| Al Jazeera Mubasher Broadcast 2 (1080p) | Al Jazeera Media Network | [link](https://www.aljazeera.com/live/) |
| Bloomberg Originals (1080p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV Asia (720p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV Asia Live Event (720p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV Australia (270p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV EMEA Live Event (720p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV Europe (720p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV US Live Event (720p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| Bloomberg TV US Politics Live Event (720p) | Bloomberg L.P. | [link](https://www.bloomberg.com/live) |
| CBS News Bay Area (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Boston (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Chicago (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Colorado (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Detroit (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Los Angeles (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Miami (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Minnesota (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News New York (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Philadelphia (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Pittsburgh (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| CBS News Texas (720p) | CBS News (Paramount) | [link](https://www.cbsnews.com/live/) |
| DW Arabic (1080p) | Deutsche Welle | [link](https://www.dw.com/en/live-tv/channel-english) |
| DW English (1080p) | Deutsche Welle | [link](https://www.dw.com/en/live-tv/channel-english) |
| DW Espanol (1080p) | Deutsche Welle | [link](https://www.dw.com/en/live-tv/channel-english) |
| DW Russian (1080p) | Deutsche Welle | [link](https://www.dw.com/en/live-tv/channel-english) |
| Africanews French (720p) | Euronews | [link](https://www.euronews.com/live) |
| France 24 Arabic (1080p) | France Médias Monde | [link](https://www.france24.com/en/live) |
| France 24 Español (1080p) | France Médias Monde | [link](https://www.france24.com/en/live) |
| France 24 French (1080p) | France Médias Monde | [link](https://www.france24.com/en/live) |
| CNA International (1080p) | Mediacorp (Singapore) | [link](https://www.mewatch.sg/watch/channels) |
| NHK Kishou Saigai (360p) [Not 24/7] | NHK (Nippon Hōsō Kyōkai) | [link](https://www3.nhk.or.jp/news/) |
| Create (1080p) | PBS (Public Broadcasting Service) | [link](https://www.pbs.org/livestream/) |
| FNX (1080p) | PBS (Public Broadcasting Service) | [link](https://www.pbs.org/livestream/) |
| PBS National East (1080p) [Geo-blocked] | PBS (Public Broadcasting Service) | [link](https://www.pbs.org/livestream/) |
| World Channel (1080p) | PBS (Public Broadcasting Service) | [link](https://www.pbs.org/livestream/) |
| Canal 24 Horas (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Canal 24 Horas Canarias (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Canal 24 Horas Catalunya (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Clan Internacional Americas (1080p) [Geo-blocked] | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Clan TVE (1080p) [Geo-blocked] | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| La 1 (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| La 1 Canarias (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| La 1 Catalunya (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| La 2 (1080p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| La 2 Canarias (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| La 2 Catalunya (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| RNE para todos (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Radio 3 (720p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| TVE Internacional America (1080p) [Geo-blocked] | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| TVE Internacional Asia-Oceania (1080p) [Geo-blocked] | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| TVE Star (576p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| TVE Star HD (1080p) | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Teledeporte (720p) [Geo-blocked] | RTVE (Corporación Radio y Televisión Española) | [link](https://www.rtve.es/play/videos/directo/) |
| Rai 2 (576p) [Geo-blocked] | Rai (Radiotelevisione italiana) | [link](https://www.raiplay.it/dirette) |
| Rai 4 (576p) | Rai (Radiotelevisione italiana) | [link](https://www.raiplay.it/dirette) |
| Rai Movie (576p) [Geo-blocked] | Rai (Radiotelevisione italiana) | [link](https://www.raiplay.it/dirette) |
| Rai Premium (576p) [Geo-blocked] | Rai (Radiotelevisione italiana) | [link](https://www.raiplay.it/dirette) |
| Rai Storia (576p) [Geo-blocked] | Rai (Radiotelevisione italiana) | [link](https://www.raiplay.it/dirette) |
| Red Bull TV (1080p) | Red Bull Media House | [link](https://www.redbull.tv/) |
| TRT 1 (1080p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT 3 (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Arabi (1080p) [Not 24/7] | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Avaz (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Belgesel (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Diyanet Çocuk (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT EBA Ilkokul (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT EBA Lise (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT EBA Ortaokul (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Haber (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Kurdî (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Müzik (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Spor (1080p) [Geo-blocked] | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Spor Yildiz (1080p) [Geo-blocked] | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Türk (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT World (1080p) [Not 24/7] | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TRT Çocuk (720p) | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| Tabii Spor 6 (720p) [Geo-blocked] | TRT (Türkiye Radyo ve Televizyon Kurumu) | [link](https://www.trtizle.com/canli) |
| TV5 Monde Asia (Asie) (1080p) [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |
| TV5Monde Europe (1080p) [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |
| TV5Monde France Belgique Suisse Monaco (1080p) [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |
| TV5Monde Info (1080p) [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |
| TV5Monde Pacifique (1080p) [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |
| TV5Monde Style (1080p) [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |
| TiVi5 Monde [Geo-blocked] | TV5Monde | [link](https://www.tv5monde.com/) |

## Attribution

The initial list of channel URLs was sourced from
[iptv-org/iptv](https://github.com/iptv-org/iptv) (Unlicense) and then
aggressively filtered by publisher-operated hostname and the inclusion
rules above. Only streams meeting those criteria were carried over.

## Reporting a problem

If you are a publisher listed here and would like a channel removed,
open an issue and we will remove it within one business day.

## License

The playlist text in this repository is dedicated to the public domain
under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
The **streams themselves** are not ours; each is owned and operated by
its publisher under their own terms of use.
