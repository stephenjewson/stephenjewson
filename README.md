<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width">

		<title>Stephen Jewson</title>

		<link rel="canonical" href="https://stephenjewson.com/">

		<meta name="author" content="Stephen Jewson">
		<meta name="description" content="Stephen Jewson Home Page">
		<meta name="keywords" content="climate, climate change, weather, risk, insurance, cat modelling">
		<meta name="theme-color" content="darkslategrey">
		<meta name="color-scheme" content="normal">
		<meta property="og:type" content="website">
		<meta property="og:url" content="https://stephenjewson.com/">
		<meta property="og:locale" content="en_GB">

<style>
* {
	box-sizing: border-box;
}

html {
	scroll-padding-top: 36px;
	scroll-behavior: smooth;
}

body {
	font-family: Arial, Helvetica, sans-serif;
	margin: 0;
}

nav {
	position: sticky;
	top: 0;
	width: 100%;
	padding: 20px;
	background-color: darkslategrey;
	text-align: center;
	font-weight: bold;
}

nav > a {
	margin: 0 20px;
	color: white;
	text-decoration: none;
	position: relative;
}
nav > a:visited {
	color: white;
}
nav > a::before {
	background-color: white;
	content: ' ';
	height: 2px;
	position: absolute;
	bottom: 0;
	transition: 0.3s ease-in-out;
	width: 0%;
}
nav > a:hover::before {
	width: 100%;
}

main {
	margin: 0 auto;
	max-width: 100ch;
	color: #141414;
}

section {
	border-bottom: 1px solid lightslategrey;
	padding: 24px 16px;
}

h2 {
	font-size: 1.17em;
	text-align: center;
	margin: 20px 0 20px 0;
}
h2 > a {
	color: inherit;
	opacity: 0;
	transition: opacity 0.3s ease;
	text-decoration: none;
}
h2 > a:visited {
	color: inherit;
}
h2 > .aligner {
	visibility: hidden;
}
h2:hover > a {
	opacity: 1;
}

li {
	margin: 10px 0;
}

p {
	text-align: justify;
}

a {
	color: #1164D1;
}
a:visited {
	color: #664085;
}

footer {
	margin: 36px 0 16px 0;
	color: slategrey;
	font-style: italic;
	text-align: center;
}

#weather-derivative-valuation > img {
	float: left;
	margin-right: 15px;
}
/* Prevent the bullet points overlapping the image */
#weather-derivative-valuation > ul {
	overflow: hidden;
}

#filter_form {
	display: flex;
	flex-flow: row wrap;
	margin: 32px 0;
}
#filter_form > label {
	flex: 1 1 auto;
}
</style>
	<body>
		<nav>
			<a href="#about">About Me</a>
			<a href="#highlights">Research Highlights</a>
			<a href="#publications">Publications</a>
			<a href="#contact">Contact</a>
		</nav>

		<main>
			<section id="about">
				<h2>About Me</h2>
				<p>
					I’m a research scientist, and spend most of my time doing research and writing journal papers on topics related to <b>weather, climate, climate change, risk and risk modelling</b>.
					Most of my research is focussed on solving science questions that come up in insurance risk modelling.
				</p>
				<p>
					I also run Lambda Climate Research Ltd, a company which supplies various outputs from my research to the insurance industry, as a way to motivate and fund my research.
					Clients get access to data, software tools, presentations, preprints, algorithms, blog posts, discussions and insights.
					Get in touch if you want to know more.  </p>
				<p>
					Prior to focussing on research I spent 22 years working in the insurance
					industry, in various roles related to the mathematical modelling of weather
					risks. For 15 years I led the RMS climate risk model development team. Prior
					to that I worked in climate research and taught mathematics at Oxford University. 
					I have a PhD on coupled climate modelling from the
					Physics Department of Oxford University, and a degree and masters in maths from
					Cambridge University.
				</p>
				<p>I use LinkedIn to post updates on my research.</p>
			</section>

			<section id="highlights">
				<h2>Research Highlights</h2>
				<p>
					Some of the more interesting highlights from the research I’ve done over the
					years are as follows (the numbers refer to papers in the list of
					publications below):
				</p>
				<ol type="1">
					 <li>Showing that when climate projections for <b>tropical cyclone</b> numbers show decreases, the number of landfalls may well still increase [152].
					 <li>Showing that climate projections for changes in <b>tropical cyclone</b> frequency and mean intensity actually give the same information [148,151].
					 <li>Showing that when <b>tropical cyclone</b> mean intensity increases, the risk may still go down (and hence that mean intensity is not really a useful metric) [148,151].
					 <li>Inventing various new methods for simulating <b>tropical cyclone tracks</b>, <b>tropical cyclone rainfall</b>, and <b>clustering</b> [114, 131, 133] .</li>
					 <li>Inventing various simulation methods for use in <b>catastrophe modelling</b>, such as
					 	<a href="https://en.wikipedia.org/wiki/Year_loss_table#YLT_Importance_Sampling"><b>YLT Importance Sampling</b></a> [139],
					 	<a href="https://en.wikipedia.org/wiki/Year_loss_table#Stochastic_Parameter_YLTs"><b>Stochastic Parameter YLTs</b></a> [150],
					 	<a href="https://en.wikipedia.org/wiki/Year_loss_table#Repeat_and_Delete"><b>Repeat and Delete</b></a> [150] and
					 	<a href="https://en.wikipedia.org/wiki/Year_loss_table#Incremental_Simulation"><b>Incremental Simulation</b></a> [154].</li>
					 <li>Solving the decision theory problem “should I <b>decide now or wait for the next forecast?</b>”, and demonstrating an algorithm that implements the solution [142]. 
						We also showed that weather forecasts would be more useful if they contained information about possible changes.</li>
					 <li>Inventing the <a href="https://en.wikipedia.org/wiki/Nonhomogeneous_Gaussian_regression"><b>non-homogeneous Gaussian regression model</b></a>, that has become widely used as a way to produce well calibrated probabilistic weather forecasts [22] .</li>
					 <li>Inventing the statistical method <a href="https://en.wikipedia.org/wiki/Directional_component_analysis"><b>Directional Component Analysis (DCA)</b></a>, which is similar to PCA, but involves a metric. DCA is useful for finding patterns of extremes in space-time datasets, such as historical climate data-sets and ensemble predictions and projections [140,144,153] .</li>
					 <li>Demonstrating that model averaging can make uncertain estimates of recent <b>climate trends</b> [95], and uncertain projections of future climate [143], more accurate, using new methods for model averaging [124,143].</li>
					 <li>Deriving expressions for the pricing of <b>weather derivatives</b> for many different underlying distributions [25, 26, 39, 46, 47, 66, 67, 120], 
 						and the differential equation that governs the price of weather options on weather swaps in a perfect market (aka the <b>weather derivatives Black-Scholes equation</b>) [27] .</li>
				</ol>
			</section>

			<div id="publications">
				<section id="weather-derivative-valuation">
					<h2>Our Book on Weather Derivatives</h2>

					<img src="http://stephenjewson.com/weather_derivative_valuation.jpg" alt="Cover of Weather Derivative Valuation" width="134" height="192">
					<p><cite>Weather Derivative Valuation</cite>, by Stephen Jewson and Anders Brix, with Christine Ziehmann.</p>
					<p>Follow one of these links to purchase:
						<ul>
							<li><a href="https://www.cambridge.org/us/catalogue/catalogue.asp?isbn=0521843715" target="_blank">Cambridge Univ Press-US</a></li>
							<li><a href="https://www.cambridge.org/gb/academic/subjects/economics/finance/weather-derivative-valuation-meteorological-statistical-financial-and-mathematical-foundations?format=PB" target="_blank">Cambridge Univ Press-UK</a></li>
							<li><a href="https://www.amazon.com/exec/obidos/tg/detail/-/0521843715/qid=1112798182/sr=8-3/ref=sr_8_xs_ap_i3_xgl14/002-3306303-5994454?v=glance&amp;s=books&amp;n=507846" target="_blank">Amazon.com</a></li>
							<li><a href="https://www.amazon.co.uk/exec/obidos/ASIN/0521843715/qid=1112797898/sr=8-1/ref=sr_8_xs_ap_i1_xgl/026-6031190-6707666" target="_blank">Amazon.co.uk</a></li>
						</ul>
					<p>Profits from the sales of this book are donated to <a href="https://www.centrepoint.org.uk/" target="_blank">Centrepoint</a>, a charity for socially excluded young people in London.</p>
				</section>

				<section id="papers">
					<h2>Papers</h2>

					<form id="filter_form">
						<label><input type="radio" name="category" value="all" checked>All</label>
						<label><input type="radio" name="category" value="pr">Peer Reviewed</label>
						<label><input type="radio" name="category" value="cm">Cat Modelling</label>
						<label><input type="radio" name="category" value="wd">Weather Derivatives</label>
						<label><input type="radio" name="category" value="cl">Climate</label>
						<label><input type="radio" name="category" value="hu">Hurricanes</label>
						<label><input type="radio" name="category" value="wf">Weather Forecasting</label>
					</form>

					<ul id='papers_list'>
						<li class="pr cm cl hu">(158) S. Jewson (2024): <cite>Projecting future tropical cyclone frequencies by combining uncertain empirical estimates of baseline frequencies with
							climate model estimates of change:
							</cite><a href="https://doi.org/10.63024/m9wk-3420" target="_blank">Journal of Catastrophe Risk and Resilience</a>
						<li class="pr cm cl hu">(157) S. Jewson (2023): <cite>The Impact of Projected Changes in Hurricane Frequencies on U.S. Hurricane Wind and Surge Damage:
							</cite><a href="https://doi.org/10.1175/JAMC-D-23-0087.1" target="_blank">Journal of Applied Meteorology and Climatology</a>
						<li class="pr cl">(156) S. Jewson, T. Maynard, F. Dottori (2023): <cite>A service to help insurers understand the financial impacts of changing flood risk in Europe, based on PESETA IV
						</cite><a href="https://doi.org/10.1016/j.cliser.2023.100395" target="_blank">Climate Services</a>
							// <a href="https://doi.org/10.5281/zenodo.7954251" target="_blank">data</a>
						<li class="pr cl">(155) S. Jewson (2023): <cite>Tropical Cyclones and Climate Change: Global Landfall Frequency Projections Derived from Knutson et al. (2020).
						</cite><a href="https://doi.org/10.1175/BAMS-D-22-0189.1" target="_blank">Bulletin of the American Meteorological Society</a>
						<li class="pr cm cl hu">(154) S. Jewson (2023): <cite>A new simulation algorithm for more precise estimates of change in catastrophe risk models, with application to hurricanes and climate change:
							</cite> <a href="https://doi.org/10.1007/s00477-023-02409-0" target="_blank">Stochastic Environmental Research and Risk Assessment</a>
							// <a href="https://rdcu.be/c6wIg" target="_blank">Free to view version</a>
							<li class="pr cl">(153) S. Jewson, G. Messori, G. Barbato, P. Mercogliano, J. Mysiak and M. Sassi  (2022): <cite>Developing Representative Impact Scenarios From Climate Projection Ensembles, With Application to UKCP18 and EURO-CORDEX Precipitation:
							</cite><a href=" https://doi.org/10.1029/2022MS003038" target="_blank">Journal of Advances in Modeling Earth Systems</a>
						<li class="pr cm cl hu">(152) S. Jewson (2022): <cite>Conversion of the Knutson et al. Tropical Cyclone Frequency Projections to North Atlantic Landfall:
							</cite><a href="https://doi.org/10.1175/JAMC-D-22-0056.1" target="_blank">Journal of Applied Meteorology and Climatology</a>
						<li class="pr cm cl hu">(151) S. Jewson (2022): <cite>The Interpretation and Implications of the Knutson et al. 2020 Projections of Changes in the Frequency and Intensity of Tropical Cyclones Under Climate Change:
							</cite><a href="https://rmets.onlinelibrary.wiley.com/doi/10.1002/qj.4299" target="_blank">Quarterly Journal of the Royal Meteorological Society</a>
						<li class="pr cm cl hu">(150) S. Jewson (2022): <cite>Application of Uncertain Hurricane Climate Change Projections to Catastrophe Risk Models:
							</cite> <a href="https://doi.org/10.1007/s00477-022-02198-y" target="_blank">Stochastic Environmental Research and Risk Assessment</a>
							// <a href="https://rdcu.be/cJGMY" target="_blank">Free to view version</a>
						<li class="pr wf">(149) S. Jewson, S. Scher and G. Messori (2021): <cite>Communicating Properties of Changes in Lagged Weather Forecasts</cite>: <a href="https://doi.org/10.1175/WAF-D-21-0086.1" target="_blank">Weather and Forecasting</a> 
						<li class="pr cm cl hu">(148) S. Jewson (2021): <cite>Interpretation of the Knutson et al. (2020) Hurricane Projections, the Impact on Annual Maximum Wind-Speed, and the Role of Uncertainty:
							</cite>: <a href="https://doi.org/10.1007/s00477-021-02142-6" target="_blank">Stochastic Environmental Research and Risk Assessment</a>
							// <a href="https://rdcu.be/cB729" target="_blank">Free to view version</a>
						<li class="pr cm cl">(147) S. Jewson, F. Comola, B. Parkes (2021): <cite>Estimating present-day European seasonal mean rainfall by combining historical data and climate model simulations, for risk assessment</cite>: <a href="https://doi.org/10.1002/met.2031" target="_blank">Meteorological Applications</a></li>
						<li class="pr cm cl hu">(146) S. Jewson (2021): <cite>Conversion of the Knutson et al. (2020) Tropical Cyclone Climate Change Projections to Risk Model Baselines</cite>: <a href="https://doi.org/10.1175/JAMC-D-21-0102.1" target="_blank">Journal of Applied Meteorology and Climatology</a> 
							// <a href="https://www.stephenjewson.com/k.html" target="_blank">online software tool</a>
							// <a href="https://doi.org/10.5281/zenodo.4757343" target="_blank">Knutson et al. data</a>
							// <a href="https://doi.org/10.5281/zenodo.5578889" target="_blank">baseline conversion software source codes</a></li>
						<li class="pr cm cl">(145) S. Jewson, T. Dallafior, F. Comola (2021): <cite>Dealing with Trend Uncertainty in Empirical Estimates of European Rainfall Climate for Insurance Risk Management</cite>: <a href="https://doi.org/10.1002/met.2008" target="_blank">Meteorological Applications</a></li>
						<li class="pr wf">(144) S. Scher, S. Jewson, G. Messori (2021): <cite>Robust worst-case scenarios from ensemble forecasts</cite>: <a href="https://doi.org/10.1175/WAF-D-20-0219.1" target="_blank">Weather and Forecasting</a></li>
						<li class='pr cm cl'>(143) S. Jewson, B. Giuliana, P. Mercogliano, J. Mysiak, M. Sassi (2021): <cite>Improving the Potential Accuracy and Usability of EURO-CORDEX Estimates of Future Rainfall Climate using Mean Squared Error Model Averaging</cite>: <a href="https://doi.org/10.5194/npg-2021-12" target="_blank">Nonlinear Processes in Geophysics</a></li>
						<li class='pr wf'>(142) S. Jewson, S. Scher and G. Messori (2021): <cite>Decide Now or Wait for the Next Forecast? Testing A Decision Framework Using Real Forecasts and Observations</cite>: <a href="https://doi.org/10.1175/MWR-D-20-0392.1" target="_blank">Monthly Weather Review</a></li>
						<li class='pr cm hu'>(141) S. Jewson and N. Lewis (2020): <cite>Statistical Decomposition of the Recent Increase in the Intensity of Tropical Storms</cite>: <a href=" https://doi.org/10.3390/oceans1040021" target="_blank">Oceans</a></li>
						<li class='pr cl'>(140) S. Jewson (2020): <cite>An Alternative to PCA for Estimating Dominant Patterns of Climate Variability and Extremes, with Application to U.S. and China Seasonal Rainfall</cite>: <a href="https://doi.org/10.3390/atmos11040354" target="_blank">Atmosphere</a></li>
						<li class='pr cm hu'>(139) S. Jewson, C. Barnes, S. Cusack and E. Bellone (2019): <cite>Adjusting catastrophe model ensembles using importance sampling, with application to damage estimation for varying levels of hurricane activity</cite>: <a href="https://doi.org/10.1002/met.1839" target="_blank">Meteorological Applications</a></li>
						<li class='pr cm cl'>(138) M. Sassi, L. Nicotina, P. Pall, D. Stone, A. Hilberts, M. Wehner, S. Jewson (2019): <cite>Impact of climate change on European winter and summer flood losses</cite>: <a href="https://doi.org/10.1016/j.advwatres.2019.05.014" target="_blank">Advances in Water Resources</a></li>
						<li class='pr cm'>(137) S. Zanardo, L. Nicotina, A. Hilberts and S. Jewson (2019): <cite>Modulation of Economic Losses from European Floods by the North Atlantic Oscillation</cite>: <a href="https://doi.org/10.1029/2019GL081956" target="_blank">Geophysical Research Letters</a></li>
						<li class='pr'>(136) G. Messori1, R. Caballero, F. Bouchet, D. Faranda, R. Grotjahn, N. Harnik, S. Jewson, J. Pinto, G. Riviere, T.Woollings, P. Yiou (2018): <cite>An interdisciplinary approach to the study of extreme weather events: large-scale atmospheric controls and insights from dynamical systems theory and statistical mechanics</cite>: <a href="https://doi.org/10.1175/BAMS-D-17-0296.1" target="_blank">Bulletin of the American Meteorological Society</a></li>
						<li class='cm '>(135) N. Shome, M. Rahnama, S. Jewson and P. Wilson(2018): <cite> <a href="https://doi.org/10.1016/B978-0-12-804071-3.00001-X" target="_blank"><cite>Quantifying Model Uncertainty and Risk</cite></a></cite>: a book chapter in <cite>Risk Modeling for Hazards and Disasters <cite>Hurricanes and Climate Change</cite></cite></li>
						<li class='pr cm'>(134) J. Kaczmarska, S. Jewson and E. Bellone (2017): <cite>Quantifying the sources of simulation uncertainty in natural catastrophe models</cite>: <a href="https://doi.org/10.1007/s00477-017-1393-0" target="_blank">Stochastic Environmental Research and Risk Assessment</a></li>
						<li class='pr cm hu'>(133) S. Khare, A. Bonazzi, C. Mitas and S. Jewson (2015): <cite>Modelling clustering of natural hazard phenomena and the effect on re/insurance loss perspectives</cite>: <a href="https://doi.org/10.5194/nhess-15-1357-2015" target="_blank">Natural Hazards and Earth System Science</a></li>
						<li class='cl '>(132) S. Jewson (2013): <cite>A Simple Method for Eliminating Double Counting in Multi-Model Ensemble Forecasts</cite>: <a href="https://www.academia.edu/4440585/_127_A_Simple_Method_for_Eliminating_Double_Counting_in_Multi-Model_Ensemble_Forecasts" target="_blank">academia.edu</a></li>
						<li class='pr cm hu'>(131) J. Grieser and S. Jewson (2012): <cite>The RMS TC-rain model: </cite><a href="https://doi.org/10.1127/0941-2948/2012/0265" target="_blank">Meteorologische Zeitschrift</a></li>
						<li class='pr cm hu'>(130) K. Coughlin, E. Bellone, T. Laepple, S. Jewson and K. Nzerem (2009): <cite>A relationship between all Atlantic hurricanes and those that make landfall in the USA</cite>: <a href="http://onlinelibrary.wiley.com/doi/10.1002/qj.367/pdf" target="_blank">Quarterly Journal of the Royal Meteorological Society</a></li>
						<li class='pr cm'>(129) A. Bonazzi, S. Cusack, C. Mitas and S. Jewson (2012): <cite>The spatial structure of European wind storms as characterized by bivariate extreme-value copulas</cite>: <a href="http://www.nat-hazards-earth-syst-sci.net/12/1769/2012/nhess-12-1769-2012.pdf" target="_blank">Natural Hazards and Earth System Science</a></li>
						<li class='pr cm hu'>(128) S. Khare, A. Bonazzi, N. West, E. Bellone and S. Jewson (2009): <cite>On the Prediction of Over-Ocean Hurricane Surface Winds and their Uncertainty</cite>: <a href="http://onlinelibrary.wiley.com/doi/10.1002/qj.442/abstract" target="_blank">Quarterly Journal of the Royal Meteorological Society</a></li>
						<li class='cl'>(127) S. Jewson and E. Hawkins (2010): <cite>Uncertain Climate Forecasts from Multi-Model Ensembles: When to Use Them and When to Ignore Them</cite>: <a href="http://arxiv.org/pdf/1006.5327v1" target="_blank">arxiv</a></li>
						<li class='cl'>(126) S. Jewson, D. Rowlands and M. Allen (2009): <cite>Objective Climate Model Predictions Using Jeffreys' Prior: the General Multivariate Normal Case</cite>: <a href="http://arxiv.org/pdf/1005.3907" target="_blank">arxiv</a></li>
						<li class='cl'>(125) S. Jewson, D. Rowlands and M. Allen (2009): <cite>Objective Probabilistic Forecasts of Future Climate Based on Jeffreys' Prior: the Case of Correlated Observables</cite>: <a href="http://arxiv.org/pdf/1005.2354" target="_blank">arxiv</a></li>
						<li class='cl'>(124) S. Jewson and E. Hawkins (2009): <cite>Improving Uncertain Climate Forecasts Using a New Minimum Mean Square Error Estimator for the Mean of the Normal Distribution</cite>: <a href="http://arxiv.org/pdf/0912.4395" target="_blank">arxiv</a></li>
						<li class='cl '>(123) S. Jewson and E. Hawkins (2009): <cite>Improving the expected accuracy of forecasts of future climate using a simple bias-variance tradeoff</cite>: <a href="http://arxiv.org/pdf/0911.1904" target="_blank">arxiv</a></li>
						<li class='cl '>(122) S. Jewson and E. Hawkins (2009): <cite>CMIP3 ensemble spread, model similarity, and climate prediction uncertainty</cite>: <a href="http://arxiv.org/pdf/0909.1890" target="_blank">arxiv</a></li>
						<li class='cl '>(121) S. Jewson, D. Rowlands and M. Allen (2009): <cite>A new method for making objective probabilistic climate forecasts from numerical climate models based on Jeffreys' Prior</cite>: <a href="http://arxiv.org/pdf/0908.4207" target="_blank">arxiv</a></li>
						<li class='wd '>(120) S. Jewson (2008): <cite>Closed-form expressions for the pricing of weather derivatives: the expected payoff for t-distributed indices</cite>: <a href="http://ssrn.com/abstract=1212528" target="_blank">ssrn</a></li>
						<li class='wd'>(119) S. Jewson (2008): <cite>Weather derivative pricing and the modelling of trends: objective Bayesian versions of the flat-line, linear trend and damped linear trend models</cite>: <a href="http://ssrn.com/abstract=1212523" target="_blank">ssrn</a></li>
						<li class='pr cm cl hu'>(118) Laepple, T., S. Jewson and K. Coughlin (2007): <cite>Interannual temperature predictions using the IPCC multi-model ensemble mean</cite>: <a href="https://doi.org/10.1029/2008GL033576" target="_blank">Geophysical Research Letters</a></li>
						<li class='pr cm hu'>(117) Jewson, S., E. Bellone, S. Khare, T. Laepple, M. Lonfat, K. Nzerem, A. O'Shay, J. Penzer, K. Coughlin (2007): <a href="http://stephenjewson.com/articles/113.pdf" target="_blank">5 Year Prediction of the Number of Hurricanes Which Make US Landfall</a>, a chapter in <cite>Hurricanes and Climate Change</cite>, editor J. Elsner,</li>
						<li class='pr cm hu'>(116) Hall, T. and Jewson, S. (2007): <cite>Comparison of Local and Basin-wide methods for Risk Assessment of Tropical Cyclone Landfall</cite>: <a href="https://doi.org/10.1175/2007JAMC1720.1" target="_blank">Journal of Applied Meteorology and Climatology</a></li>
						<li class='cm hu'>(115) Hall, T. and Jewson, S. (2007): <cite>SST and North American Tropical Cyclone Landfall: A Statistical Modelling Study</cite>: <a href="http://arxiv.org/abs/0801.1013" target="_blank">arxiv</a></li>
						<li class='pr cm hu'>(114) Hall, T. and Jewson, S. (2007): <cite>Statistical Modelling of North American Tropical Cyclone Tracks</cite>: <a href=" https://doi.org/10.1111/j.1600-0870.2007.00240.x" target="_blank">Tellus</a></li>
						<li class='cm hu'>(113) Nzerem, K., Jewson, S. and Laepple, T. (2007): <cite>Predicting landfalling hurricane numbers from sea surface temperature: a theoretical comparison of direct and indirect approaches</cite>: <a href="http://www.arxiv.org/abs/physics/0701176" target="_blank">arxiv</a></li>
						<li class='cm hu'>(112) Laepple, T., Bellone, E., Jewson, S. and Nzerem, K. (2007): <cite>Correlations between hurricane numbers and sea surface temperature: why does the correlation disappear at landfall?</cite>:&nbsp;<a href="http://www.arxiv.org/abs/physics/0701175" target="_blank">arxiv</a></li>
						<li class='cm hu'>(111) Binter, R., Jewson, S., and Khare, S. (2007): <cite>Statistical modelling of the relationship between main development region sea surface temperature and landfalling Atlantic basin hurricane numbers</cite>: <a href="http://www.arxiv.org/abs/physics/0701173" target="_blank">arxiv</a></li>
						<li class='cm hu '>(110) Binter, R., Jewson, S., and Khare, S. (2007): <cite>Predicting basin and landfalling hurricane numbers from sea surface temperature</cite>: <a href="http://www.arxiv.org/abs/physics/0701170" target="_blank">arxiv</a></li>
						<li class='cm hu'>(109) Jewson, S. (2007): <cite>Predicting hurricane numbers from sea surface temperature: closed-form expressions for the mean, variance and standard error of the number of hurricanes</cite>: <a href="http://www.arxiv.org/abs/physics/0701167" target="_blank">arxiv</a></li>
						<li class='cm hu'>(108) Laepple, T., Jewson, S., Penzer, J., Bellone, E. and Nzerem, K. (2007): <cite>Predicting landfalling hurricane numbers from basin hurricane numbers: statistical analysis and predictions</cite>: <a href="http://www.arxiv.org/abs/physics/0701166" target="_blank">arxiv</a></li>
						<li class='cm cl hu'>(107) Laepple, T. and Jewson, S. (2007): <cite>Five year ahead prediction of sea surface temperature in the tropical Atlantic: a comparison between IPCC climate models and simple statistical methods</cite>: <a href="http://www.arxiv.org/abs/physics/0701165" target="_blank">arxiv</a></li>
						<li class='cm cl hu'>(106) Laepple, T., Jewson, S., Meagher, J., O'Shay, A. and Penzer, J. (2007): <cite>Five year prediction of sea surface temperature in the tropical Atlantic: a comparison of simple statistical methods</cite>: <a href="http://www.arxiv.org/abs/physics/0701162" target="_blank">arxiv</a></li>
						<li class='cm hu'>(105) Nzerem, K., Jewson, S. and Laepple, T. (2006): <cite>Change-point detection in the historical hurricane number time-series: why can't we detect change-points at US landfall? </cite>: 
						<a href="http://www.arxiv.org/abs/physics/0611107" target="_blank">arxiv</a></li>
						<li class='wd '>(104) Jewson, S. and Penzer, J. (2006): <cite>Weather derivative pricing and the normal distribution: comparing three fitting schemes using the out-of-sample log-likelihood scoring system</cite>: <a href="http://ssrn.com/abstract=944007" target="_blank">ssrn</a></li>
						<li class='cm hu'>(103) Hall, T. and Jewson, S. (2006): <cite>Predicting hurricane regional landfall rates: comparing local and basin-wide track model approaches</cite>: <a href="http://www.arxiv.org/abs/physics/0611103" target="_blank">arxiv</a></li>
						<li class='cm hu'>(102) Jewson, S. and Penzer, J. (2006): <cite>An objective change-point analysis of landfalling historical Atlantic hurricane numbers</cite>: <a href="http://www.arxiv.org/abs/physics/0611086" target="_blank">arxiv</a></li>
						<li class='cm hu'>(101) Jewson, S. and Penzer, J. (2006): <cite>An objective change-point analysis of historical Atlantic hurricane numbers</cite>: <a href="http://www.arxiv.org/abs/physics/0611071" target="_blank">arxiv</a></li>
						<li class='cm hu'>(100) Binter, R., Jewson, S., Khare, S., O'Shay, A. and Penzer, J: (2006): <cite>Year ahead prediction of US landfalling hurricane numbers: the optimal combination of multiple levels of activity since 1900</cite>: <a href="http://www.arxiv.org/abs/physics/0611070" target="_blank">arxiv</a></li>
						<li class='cm hu'>(99) Hall, T. and Jewson, S. (2006): <cite>Comparing classical and Bayesian methods for predicting hurricane landfall rates</cite>: <a href="http://arxiv.org/abs/physics/0611006" target="_blank">arxiv</a></li>
						<li class='wd '>(98) Jewson, S. and Penzer, J. (2006): <cite>Weather derivative pricing and the normal distribution: fitting the variance to maximise expected predictive log-likelihood</cite>: <a href="http://ssrn.com/abstract=911569" target="_blank">ssrn</a></li>
						<li class='cm hu'>(97) Jewson, S., Penzer, J. and Casey, C. (2006): <cite>Year ahead prediction of US landfalling hurricane numbers: the optimal combination of long and short baselines for intense hurricanes</cite>: <a href="http://www.arxiv.org/abs/physics/0606192" target="_blank">arxiv</a></li>
						<li class='cm hu '>(96) Meagher, J. and Jewson, S. (2006): <cite>Year-ahead prediction of hurricane season sea surface temperature in the tropical Atlantic</cite>: <a href="http://www.arxiv.org/abs/physics/0606185" target="_blank">arxiv</a></li>
						<li class='pr wd'>(95) Jewson, S. and Penzer, J. (2006): <cite>Estimating trends in weather series: consequences for pricing derivatives</cite>: Studies in Non-linear Dynamics and Econometrics</li>
						<li class='cm hu'>(94) Jewson, S., Casey, C. and Penzer, J. (2005): <cite>Year ahead prediction of US landfalling hurricane numbers: the optimal combination of long and short baselines</cite>: <a href="http://www.arxiv.org/abs/physics/0512113" target="_blank">arxiv</a></li>
						<li class='wd '>(93) Jewson, S. (2006): <cite>The</cite><cite>Modelling of Weather Derivative Portfolio Risk</cite>: a chapter in 'Risk and Portfolio Management', a book published by Springer Verlag</li>
						<li class='cm hu'>(92) Khare, S. and Jewson, S. (2005): <cite>Year ahead prediction of US landfalling hurricane numbers: intense hurricanes</cite>: <a href="http://www.arxiv.org/abs/physics/0512092" target="_blank">arxiv</a></li>
						<li class='cm hu'>(91) Hall, T, and Jewson, S. (2005): <cite>Statistical modelling of tropical cyclone tracks: non-normal innovations</cite>: <a href="http://www.arxiv.org/abs/physics/0512135" target="_blank">arxiv</a></li>
						<li class='cm hu'>(90) Hall, T, and Jewson, S. (2005): <cite>Statistical modelling of tropical cyclone tracks: modelling cyclone lysis</cite>: <a href="http://www.arxiv.org/abs/physics/0512091" target="_blank">arxiv</a></li>
						<li class='hu cm'>(89) Hall, T, and Jewson, S. (2005): <cite>Statistical modelling of tropical cyclone genesis: a non-parametric model for the annual distribution</cite>: <a href="http://www.arxiv.org/abs/physics/0510203" target="_blank">arxiv</a></li>
						<li class='cm hu '>(88) Hall, T, and Jewson, S. (2005): <cite>Statistical modelling of tropical cyclone tracks: modelling the autocorrelation in track shape</cite>: <a href="http://www.arxiv.org/abs/physics/0509024" target="_blank">arxiv</a></li>
						<li class='wd '>(87) Jewson, S. <cite>Pricing the Weather</cite>: Energy Risk, August 2005</li>
						<li class='wd '>(86) Jewson, S., and Jones, S. (2005): <cite>Weather derivatives and carbon emissions trading</cite>: a chapter in <cite>The Finance of Climate Change</cite>, a book published by RiskBooks</li>
						<li class='cm '>(85) Khare, S. and Jewson, S. (2005): <cite>Year ahead prediction of US landfalling hurricane numbers</cite>: <a href="http://www.arxiv.org/abs/physics/0507165" target="_blank">arxiv</a></li>
						<li class=' '>(84) Jewson, S. (2005): <cite>Improving on the empirical covariance matrix using truncated PCA with white noise residuals</cite>: <a href="http://www.arxiv.org/abs/physics/0506055" target="_blank">arxiv</a></li>
						<li class='wd '>(83) Jewson, S. and Whitehead, D. <cite>Taking the measure of data</cite>: <a href="http://www.stephenjewson.com/articles/79.pdf" target="_blank">Environmental Finance April 2004</a></li>
						<li class='cm '>(82) Hall, T, and Jewson, S. (2005): <cite>Statistical modelling of tropical cyclone tracks: a comparison of models for the variance of trajectories</cite>: <a href="http://www.arxiv.org/abs/physics/0505103" target="_blank">arxiv</a></li>
						<li class='wd '>(81) Jewson, S. and Khare, S. (2005): <cite>Weather derivative pricing and the impact of El Nino on US temperature: empirical tests
						of an optimal categorical forecasting scheme</cite>: <a href="http://ssrn.com/abstract=695744" target="_blank">ssrn</a></li>
						<li class='cm '>(80) Hall, T, and Jewson, S. (2005): <cite>Statistical modelling of tropical cyclone tracks: a semi-parametric model for the mean trajectory</cite>: <a href="http://www.arxiv.org/abs/physics/0503231" target="_blank">arxiv</a></li>
						<li class='wd '>(79) Jewson, S. and Penzer, J. (2005): <cite>Weather derivative pricing and the impact of El Nino on US temperature: the statistics of optimal categorical predictions</cite>: <a href="http://ssrn.com/abstract=653242" target="_blank">ssrn</a></li>
						<li class='wd '>(78) Jewson, S. and Penzer, J. (2005): <cite>Weather derivative pricing and the detrending of meteorological data: three alternative representations of damped linear detrending</cite>: <a href="http://ssrn.com/abstract=653241" target="_blank">ssrn</a></li>
						<li class='wd '>(77) Jewson, S. and Penzer, J. (2004): <cite>Weather derivative pricing and the detrending of meteorological data: a comparison of predictions based on local and global trend estimates</cite>: <a href="http://ssrn.com/abstract=623401" target="_blank">ssrn</a></li>
						<li class='wd '>(76) Jewson, S. and Penzer, J. (2004): <cite>Weather derivative pricing and the detrending of meteorological data: an empirical evaluation of damped linear detrending</cite>: <a href="http://ssrn.com/abstract=623381" target="_blank">ssrn</a></li>
						<li class='wd '>(75) Jewson, S. and Penzer, J. (2004): <cite>Weather derivative pricing and the detrending of meteorological data: closed-form solutions for the behaviour of a simple decision rule</cite>: <a href="http://ssrn.com/abstract=618592" target="_blank">ssrn</a></li>
						<li class='wd '>(74) Jewson, S. and Penzer, J. (2004): <cite>Weather derivative pricing and a preliminary investigation into a decision rule for detrending</cite>: <a href="http://ssrn.com/abstract=618590" target="_blank">ssrn</a></li>
						<li class='wf '>(73) Jewson, S. (2004): <cite>Probabilistic forecasting of temperature: a comparison of four spread regression models</cite>: <a href="http://www.arxiv.org/abs/physics/0410053" target="_blank">arxiv</a></li>
						<li class='wf '>(72) Jewson, S. (2004): <cite>Probabilistic forecasting of temperature: measuring the utility of the ensemble spread</cite>: <a href="http://www.arxiv.org/abs/physics/0410039" target="_blank">arxiv</a></li>
						<li class='wf '>(71) Jewson, S. (2004): <cite>Probabilistic forecasting of temperature: comments on the Bayesian model averaging approach</cite>: <a href="http://www.arxiv.org/abs/physics/0409127" target="_blank">arxiv</a></li>
						<li class='wf '>(70) Jewson, S. (2004): <cite>Making use of the information in ensemble weather forecasts: comparing the end to end and full statistical modelling approaches</cite>: <a href="http://www.arxiv.org/abs/physics/0409097" target="_blank">arxiv</a></li>
						<li class='wf '>(69) Jewson, S. (2004): <cite>Probabilistic temperature forecasting: a summary of our recent research results</cite>: <a href="http://www.arxiv.org/abs/physics/0409096" target="_blank">arxiv</a></li>
						<li class='wd '>(68) Jewson, S. (2004): <cite>Arbitrage pricing of weather derivatives and the stochastic process for the expectation of non-linear weather indices</cite>: <a href="http://ssrn.com/abstract=593317" target="_blank">ssrn</a></li>
						<li class='wd '>(67) Jewson, S. (2004): <cite>Closed-form expressions for the pricing of weather derivatives: the payoff variance for gamma distributed indices</cite>: <a href="http://ssrn.com/abstract=576662" target="_blank">ssrn</a></li>
						<li class='wd '>(66) Jewson, S. (2004): <cite>Closed-form expressions for the pricing of weather derivatives: the expected payoff for gamma distributed indices</cite>: <a href="http://ssrn.com/abstract=576661" target="_blank">ssrn</a></li>
						<li class='wd '>(65) Jewson, S. and Penzer, J. (2004): <cite>Following the trend, a review of our recent work on detrending</cite> <a href="http://stephenjewson.com/articles/61.pdf" target="_blank">Risk Magazine</a></li>
						<li class=' '>  (64) Jewson, S. (2004): <cite>The inaccessibility of meteorological journals to the private sector</cite>: <a href="http://stephenjewson.com/articles/60.pdf" target="_blank">Weather</a></li>
						<li class='wd '>(63) Jewson, S. and Penzer, J. (2004): <cite>Weather derivative pricing and the interpretation of linear trend models</cite>: <a href="http://ssrn.com/abstract=563962" target="_blank">ssrn</a></li>
						<li class='wd '>(62) Jewson, S. and Penzer, J. (2004): <cite>Optimal year ahead forecasting of temperature in the presence of a linear trend, and the pricing of weather derivatives</cite>: <a href="http://ssrn.com/abstract=563943" target="_blank">ssrn</a></li>
						<li class='wd '>(61) Jewson, S. and Penzer, J. (2004):Closed form expressions for the uncertainty from linear detrending, and the pricing of weather derivatives: <a href="http://ssrn.com/abstract=561841" target="_blank">ssrn</a></li>
						<li class='wd '>(60) Jewson, S. (2004): <cite>Weather derivatives and weather derivative pricing</cite>: <a href="http://stephenjewson.com/articles/56.pdf.gz" target="_blank">FSR Forum</a> </li>
						<li class='wd '>(59) Jewson, S. (2004): <cite>Introduction to weather derivative pricing</cite>: <a href="http://ssrn.com/abstract=557831" target="_blank">ssrn</a></li>
						<li class='wd '>(58) Jewson, S. and Brix. A. (2004): <cite>Weather derivative pricing and the spatial variability of US temperature trends</cite>: <a href="http://ssrn.com/abstract=535924" target="_blank">ssrn</a></li>
						<li class='wd '>(57) Jewson, S. (2004): <cite>Weather derivative pricing and the normality of standard US temperature indices</cite>: <a href="http://ssrn.com/abstract=535982" target="_blank">ssrn</a></li>
						<li class='wd '>(56) Jewson, S. (2004): <cite>Weather derivative pricing and the year ahead forecasting of temperature part 2: theory</cite>: <a href="http://ssrn.com/abstract=535143" target="_blank">ssrn</a></li>
						<li class='wd '>(55) Jewson, S. and Brix, A. (2004): <cite>Weather derivative pricing and the year ahead forecasting of temperature part 1: empirical results</cite>: <a href="http://ssrn.com/abstract=535142" target="_blank">ssrn</a></li>
						<li class='wd '>(54) Jewson, S. (2004): <cite>Weather derivative pricing and the potential accuracy of daily temperature modelling</cite>: <a href="http://ssrn.com/abstract=535122" target="_blank">ssrn</a></li>
						<li class='wd '>(53) Jewson, S. (2004): <cite>Convergence of the distribution of payoffs for portfolios of weather derivative options</cite>: <a href="http://ssrn.com/abstract=531043" target="_blank">ssrn</a></li>
						<li class='wd '>(52) Jewson, S. (2004): <cite>A preliminary assessment of the utility of seasonal forecasts for the pricing of U.S. temperature based weather derivatives</cite>: <a href="http://ssrn.com/abstract=531062" target="_blank">ssrn</a></li>
						<li class='wd '>(51) Jewson, S. (2004): <cite>The relative importance of trends, distributions and the number of years of data in the pricing of weather options</cite>: <a href="http://ssrn.com/abstract=516503" target="_blank">ssrn</a></li>
						<li class='wf '>(50) Jewson, S., Ambaum, M. and Ziehmann, C. (2004): <cite>Singular vector ensemble forecasting systems and the prediction of flow dependent uncertainty</cite>: <a href="http://www.arxiv.org/abs/physics/0402027" target="_blank">arxiv</a></li>
						<li class='wf'>(49) Jewson, S. (2004): <cite>Improving probabilistic weather forecasts using seasonally varying calibration parameters</cite>: <a href="http://www.arxiv.org/abs/physics/0402026" target="_blank">arxiv</a></li>
						<li class='wd '>(48) Jewson, S. (2004): <cite>The application of PCA to weather derivative portfolios</cite>: <a href="http://ssrn.com/abstract=0486503" target="_blank">ssrn</a></li>
						<li class='wd '>(47) Jewson, S. (2004): <cite>Closed-form expressions for the beta of a weather derivative portfolio</cite>: <a href="http://ssrn.com/abstract=486442" target="_blank">ssrn</a> </li>
						<li class='wd '>(46) Jewson, S. (2004): <cite>Closed-form expressions for the pricing of weather derivatives Part 4: the kernel density</cite>: <a href="http://ssrn.com/abstract=486422" target="_blank">ssrn</a></li>
						<li class='wd '>(45) Jewson, S. (2004): <cite>Comparing the potential accuracy of burn and index modelling for weather option valuation</cite>: <a href="http://ssrn.com/abstract=486342" target="_blank">ssrn</a></li>
						<li class='wd '>(44) Jewson, S. (2004): <cite>Four methods for the static hedging of weather derivative portfolios</cite>: <a href="http://ssrn.com/abstract=486302" target="_blank">ssrn</a></li>
						<li class='wf '>(43) Jewson, S. (2004): <cite>The problem with the Brier score</cite>: <a href="http://www.arxiv.org/abs/physics/0401046" target="_blank">arxiv</a></li>
						<li class='wd wf '>(42) Jewson, S. (2003): <cite>Weather forecasts, weather derivatives, Black-Scholes, Feynmann-Kac and Fokker-Planck</cite>: <a href="http://www.arxiv.org/abs/physics/0312125" target="_blank">arxiv</a></li>
						<li class='wd '>(41) Jewson, S. (2003): <cite>Use of the basic and adjusted kernel densities for weather derivative pricing</cite>: <a href="http://ssrn.com/abstract=481923" target="_blank">ssrn</a></li>
						<li class='wd '>(40) Jewson, S. (2003): <cite>Risk loading and implied volatility in the pricing of weather options</cite>: <a href="http://ssrn.com/abstract=481905" target="_blank">ssrn</a> </li>
						<li class='wd '>(39) Jewson. S. (2003): <cite>Closed form expressions for the pricing of weather derivatives part 3: the payoff variance</cite>: <a href="http://ssrn.com/abstract=481902" target="_blank">ssrn</a></li>
						<li class='wd '>(38) Jewson, S. (2003): <cite>Horizon value at risk for weather derivatives part 2: portfolios</cite>: <a href="http://ssrn.com/abstract=478051" target="_blank">ssrn</a></li>
						<li class='wd '>(37) Jewson, S. (2003): <cite>Horizon value at risk for weather derivatives part 1: single contracts</cite>: <a href="http://ssrn.com/abstract=477585" target="_blank">ssrn</a></li>
						<li class='wd '>(36) Jewson, S. (2003): <cite>Simple models for the volatility of weather derivative underlyings</cite>: <a href="http://ssrn.com/abstract=477163" target="_blank">ssrn</a></li>
						<li class='wd '>(35) Jewson, S., Hamlin J. and Whitehead D. (2003): <cite>Moving Stations and Making Money</cite>: <a href="http://stephenjewson.com/articles/30.zip" target="_blank">Environmental Finance Nov 2003 </a></li>
						<li class='wf '>(34) Jewson, S. (2003): <cite>Do medium range ensemble forecasts give useful predictions of temporal correlations?
						: </cite> <a href="http://www.arxiv.org/abs/physics/0310079" target="_blank">arxiv</a></li>
						<li class='wf '>(33) Jewson, S. (2003): <cite>Do probabilistic medium-range temperature forecasts need to allow for non-normality? : </cite> <a href="http://arxiv.org/abs/physics/0310060" target="_blank">arxiv</a></li>
						<li class='wf '>(32) Jewson, S. (2003): <cite>Comparing the ensemble mean and the ensemble standard deviation as inputs for probabilistic medium-range temperature forecasts</cite>: <a href="http://arxiv.org/abs/physics/0310059" target="_blank">arxiv</a></li>
						<li class='wf'>(31) Jewson, S. and Ziehmann, C. (2003): <cite>Five guidelines for the evaluation of site-specific medium range probabilistic temperature forecasts</cite>: <a href="http://arxiv.org/abs/physics/0310021" target="_blank">arxiv</a></li>
						<li class=' '>(30) Jewson, S., Brix, A. and Ziehmann, C. (2003): <cite>A note on the use of the word "likelihood" in statistics and meteorology</cite>: <a href="http://arxiv.org/abs/physics/0310020" target="_blank">arxiv</a></li>
						<li class='wf '>(29) Jewson, S. (2003): <cite>Moment based ensemble calibration methods</cite>: <a href="http://arxiv.org/abs/physics/0309042" target="_blank">arxiv</a></li>
						<li class='wd '>(28) Jewson, S. (2003): <cite>Estimation of uncertainty in the pricing of weather options</cite>: <a href="http://ssrn.com/abstract=441286" target="_blank">ssrn</a></li>
						<li class='wd '>(27) Jewson, S. and Zervos, M. (2003): <cite>The Black-Scholes equation for weather derivatives</cite>: <a href="http://ssrn.com/abstract=436282" target="_blank">ssrn</a></li>
						<li class='wd '>(26) Jewson, S. (2003): <cite>Closed form expressions for the pricing of weather derivatives: Part 2 - the greeks</cite>: <a href="http://ssrn.com/abstract=436263" target="_blank">ssrn</a></li>
						<li class='wd '>(25) Jewson, S. (2003): <cite>Closed form expressions for the pricing of weather derivatives: Part 1 - the expected payoff</cite>: <a href="http://ssrn.com/abstract=436262" target="_blank">ssrn</a></li>
						<li class='wf '>(24) Jewson, S. (2003): <cite>Use of the likelihood for measuring the skill of probabilistic forecasts</cite>: <a href="http://arxiv.org/abs/physics/0308046" target="_blank">arxiv</a></li>
						<li class='cl '>(23) Jewson, S., Doblas-Reyes, F. and Hagedorn, R. (2003): <cite>The assessment and calibration of ensemble seasonal forecasts of equatorial pacific ocean temperature and the predictability of uncertainty</cite>: <a href="http://arxiv.org/abs/physics/0308065" target="_blank">arxiv</a></li>
						<li class='pr wf'>(22) Jewson, S., Brix, A. and Ziehmann, C. (2003): <cite>A new parametric model for the assessment and calibration of medium range ensemble temperature forecasts</cite>: <a href= https://doi.org/10.1002/asl.69 target="_blank">Atmospheric Science Letters</a></li>
						<!--<li class=' '>(22) Jewson, S., Brix, A. and Ziehmann, C. (2003): <cite>A new framework for the assessment and calibration of medium range ensemble temperature forecasts</cite>: <a href="http://arxiv.org/abs/physics/0308057" target="_blank">arxiv</a></li>-->
						<li class='pr wd wf'>(21) Jewson, S. and Ziehmann, C. (2002): <cite>Using ensembles forecasts to predict forecast changes, with application to weather swap value at risk</cite>: <a href="https://doi.org/10.1016/S1530-261X(03)00003-3" target="_blank">Atmospheric Science Letters</a></li>
						<li class='pr wd wf'>(20) Jewson, S. and Ziehmann, C. (2002): <cite>Weather swap pricing and the optimal size for medium range forecast ensembles</cite>: <a href="https://doi.org/10.1175/1520-0434(2003)018%3C0675:WSPATO%3E2.0.CO;2" target="_blank">Weather and Forecasting</a></li>
						<li class='wd '>(19) Jewson, S. (2002): <cite>Weather derivative pricing and risk management: volatility and value at risk</cite>: <a href="http://ssrn.com/abstract=405802" target="_blank">ssrn</a></li>
						<li class='pr wd wf'>(18) Jewson, S. and Caballero, R. (2002): <cite>The use of weather forecasts in the pricing of weather derivatives</cite>: <a href="https://doi.org/DOI:10.1017/S1350482703001099" target="_blank">Meteorological Applications</a></li>
						<li class='pr wd'>(17) Jewson, S. and Caballero, R. (2002): <cite>Seasonality in the statistics of surface air temperature and the pricing of weather derivatives</cite>: <a href="https://doi.org/10.1017/S1350482703001105" target="_blank">Meteorological Applications </a></li>
						<li class='wd '>(16) Caballero, R. and Jewson, S. (2002): <cite>Multivariate long memory modelling of daily surface air temperatures and the valuation of weather derivative portfolios</cite>: <a href="http://ssrn.com/abstract=405800" target="_blank">ssrn</a></li>
						<li class='wd wf'>(15) Jewson, S., Brix, A. and Ziehmann, C. (2002): <cite>Use of meteorological forecasts in weather derivative pricing</cite>: <a href="http://ssrn.com/abstract=405781" target="_blank">a chapter in 'Climate Risk and the Weather Market', published by RiskBooks</a></li>
						<li class='wd '>(14) Jewson, S. (2002): <cite>Arbitrage Pricing for Weather Options</cite>: <a href="http://ssrn.com/abstract=405800" target="_blank">a chapter in 'Climate Risk and the Weather Market', published by Riskbooks [09.zip]</a></li>
						<li class='wd '>(13) Brix, A., Jewson, S. and Ziehmann, C. (2002): <cite>Weather Derivative Modelling and Valuation</cite>: <a href="http://stephenjewson.com/articles/10.zip" target="_blank">a chapter in
						'Climate Risk and the Weather Market', published by RiskBooks</a></li>
						<li class='pr wd'>(12) Caballero, R., Jewson, S. and Brix, A. (2002): <cite>Long memory in surface air temperature: Detection, modelling and application to weather
						derivative valuation</cite>: <a href="http://doi.org/10.3354/cr021127" target="_blank">Climate Research</a></li>
						<li class='wd '>(11) Jewson, S. (2002): <cite>Weather Option Pricing With Transaction Costs</cite>: <a href="http://stephenjewson.com/articles/08.zip" target="_blank">Energy Power and Risk Management 2003</a></li>
						<li class='wd '>(10) Jewson, S., Brix A. and Ziehmann, C (2002): <cite>Risk Modelling</cite>: <a href="http://stephenjewson.com/articles/07.zip" target="_blank">Weather Risk Report - Global Reinsurance Review -Feb 2002</a></li>
						<li class=' '>(9) Jewson, S. (2001): <cite>Use</cite><cite> of GCM Forecasts in Financial-Meteorological Models</cite>: <a href="http://stephenjewson.com/articles/06.zip" target="_blank">Proceedings of
						the Climate Diagnostics Workshop #25 - US Dept of Commerce</a></li>
						<li class='wd '>(8) Jewson, S. and Whitehead, D. (2001): <cite>Weather Risk and Weather Data</cite>: <a href="http://stephenjewson.com/articles/05.zip" target="_blank">Environmental Finance Feb 2001</a></li>
						<li class='wd '>(7) Jewson, S. and Brix, A. (2001): <cite>Sunny Outlook for Weather Investors? : </cite> <a href="http://stephenjewson.com/articles/04.zip" target="_blank">Environmental Finance Nov 2001</a></li>
						<li class='pr cl'>(6) Elliott, J., Jewson S. and Sutton R. (2001): <cite>The Impact of the 1997/1998 El Nino event on the Atlantic Ocean</cite>: <a href="https://doi.org/10.1175/1520-0442(2001)014%3C1069:TIOTEN%3E2.0.CO;2" target="_blank">Journal of Climate</a></li>
						<li class='pr cl'>(5) Sutton R., Norton W. and Jewson S. (2001): <cite>The North Atlantic Oscillation - What Role for the Ocean?</cite>: <a href="https://doi.org/doi:10.1006/asle.2000.0021" target="_blank">Atmospheric Science Letters</a></li>
						<li class='pr cl'>(4) Kleeman R., Wang G., and Jewson S. (2001): <cite>Surface flux response to interannual tropical Pacific Sea Surface Temperature variability in AMIP models</cite>: <a href="https://link.springer.com/article/10.1007/s003820000132" target="_blank">Climate Dynamics </a> / <a href="http://stephenjewson.com/articles/01.zip" target="_blank"> local copy </a></li>
						<li>(3) Jewson, S. (2000): <cite>Use of Meteorological Forecasts at RMS</cite>: <a href="http://stephenjewson.com/articles/03.zip" target="_blank">ECMWF conference reports</a></li>
						<li class='pr cl'>(2) Dong, B., Sutton R., Jewson S., O'Neill A. and Slingo J. (2000): <cite>Predictable winter climate in the North Atlantic sector during the 1997-1999 ENSO cycle</cite>: <a href=" https://doi.org/10.1029/1999GL010994" target="_blank">Geophysical Research Letters</a></li>
						<li class='pr cl hu'>(1) Sutton, R., Jewson S. S. and Rowell D. (2000): <cite>The Elements of Climate Variability in the Tropical Atlantic Region</cite>: <a href="https://doi.org/10.1175/1520-0442(2000)013%3C3261:TEOCVI%3E2.0.CO;2" target="_blank">Journal of Climate</a></li>
					</ul>
<script type="module">
const filter_form = document.getElementById("filter_form");

for (const label of filter_form.children) {
	label.firstElementChild.addEventListener("input", () => update_shown_papers());
}

const papers = document.getElementById("papers_list").children;
function update_shown_papers() {
	for (const label of filter_form.children) {
		label.style.textShadow = label.firstElementChild.checked ? "0px 0px 1px black" : "none";
	}

	const shown = filter_form.elements.namedItem("category").value;
	for (const paper of papers) {
		paper.style.display = shown === "all" || paper.classList.contains(shown) ? "" : "none";
	}
}
update_shown_papers();
</script>
				</section>
			</div>

			<section id="contact">
				<h2>Contact Me</h2>
				<p>firstname.surname@gmail.com</p>
			</section>

<script type="module">
for (const section of document.getElementsByTagName("section")) {
	const header = section.getElementsByTagName("h2")[0];

	const pre_anchor = document.createElement("a");
	pre_anchor.href = `#${section.id}`;
	pre_anchor.append("§");
	header.prepend(pre_anchor, " ");

	const post_aligner = document.createElement("span");
	post_aligner.append("§");
	post_aligner.classList.add("aligner");
	header.append(" ", post_aligner);
}
</script>

			<footer>© 2021 K Jewson, L Jewson, S Jewson</footer>
		</main>
	</body>
</html> 
