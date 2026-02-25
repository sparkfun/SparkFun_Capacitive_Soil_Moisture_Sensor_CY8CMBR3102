## Sensor Calibration

The Qwiic Soil Moisture Sensor (Capacitive) operates by detecting changes in capacitance in the soil it's inserted into. This works in measuring soil moisture by measuring the soil's change in [relative permittivity (or dielectric constant)](https://en.wikipedia.org/wiki/Relative_permittivity). Put simply, wet soil has a higher relative permittivity than dry soil and therefore the sensor will report higher capacitance values in wet soil. As soil dries out, it loses permittivity and the measured capacitance drops. 

Different soil types and environments can return significantly different capacitance values so it is important to calibrate the Qwiic Soil Moisture Sensor (Capacitive) to get an effective range of capacitance values for the soil it's monitoring. Start by inserting the sensor into a *completely dry* soil sample to get the minimum values for the soil. Then place the sensor into a *completely saturated* sample of the same soil to get the max values. With this range defined, you can create thresholds to trigger events like turning on the Soil Moisture Sensor's blue STAT LED when a threshold is exceeded as demonstrated in Example 03 - LED.

## General Troubleshooting

!!! note
    <span class="glyphicon glyphicon-question-sign" aria-hidden="true"></span>
        <strong> Not working as expected and need help? </strong> <br /><br />

    If you need technical assistance and more information on a product that is not working as you expected, we recommend heading on over to the <a href="https://www.sparkfun.com/technical_assistance">SparkFun Technical Assistance</a> page for some initial troubleshooting. <br /><br />

    <div style="text-align: center"><a href="https://www.sparkfun.com/technical_assistance" target="sfe_technical_assistance" class="md-button">SparkFun Technical Assistance Page</a></div>

    If you don't find what you need there, the <a href="https://community.sparkfun.com/">SparkFun Forums</a> are a great place to find and ask for help. If this is your first visit, you'll need to create a forum account to search product forums and post questions.<br /><br />

    <div style="text-align: center"><a href="https://community.sparkfun.com/" class="md-button md-button--primary">Log Into SparkFun Forums</a></div>