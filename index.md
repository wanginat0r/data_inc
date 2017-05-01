## Chart 1 - Boxplots for Quantitative Variables of Interest

# Variables include:
- Value - PM 2.5 in micrograms/cubic meter
- Tmpf - Temperature (F)
- Dwpf - Dew Point (F)
- Relh - Relative Humidity (%)
- Sped - Wind Speed (knots)
- P01m - Precipitation (in)
- Vsby - Visibility (miles)

[https://ibb.co/hsN5i5]

Note that the pollutant "value" column has entries < 0, which wouldn't make sense for an absolute pollutant scale of micrograms/cubic meter. Some of the Open AQ data needs to be checked. The pollutant data is also right-skewed - i.e. there are a small subset of days that have very high levels of pollution.

The other distributions seem mostly as expected - "sped" shows a few days where it is very windy (likely during a storm or other short-term weather event), "p01m" shows a few days where it rained heavily, and "vsby" shows that visibility is generally quite good (at about 10 miles), with a small number of days where the visibility is reduced.

## Chart 2 - Avg Pollution by Hour of Day

# 2016 data for Iowa City, IA averaged across hours for PM 2.5 pollution metric

[https://ibb.co/mwoZbQ]

This distribution looks like it could be characterized as bi-modal, with one peak around 4-6am and a slightly larger peak around 3pm. I probably would have expected air pollution to primarily peak around late afternoon/early evening when it is the warmest and when there are high levels of energy consumption and transportation. I think a closer look at data from other cities as well as other time periods may help better understand the Open AQ data.
