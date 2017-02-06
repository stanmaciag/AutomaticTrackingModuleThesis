# Visual Tracking for Mobile Robotics

Visual object tracking is a field of study, that poses subject of intensive research since a long
time, which is motivated by its wide practical application, e.g. automatic surveillance systems,
human-machine interfaces or advanced navigation. For the purposes of this thesis the
automatic tracking module for mobile robotics has been developed. The designing process
required comprehensive and interdisciplinary literature research, introduced in chapter one.
The review of conclusions is presented in the next three chapters, including general theory of
object tracking, interrelated issues from the field of digital image processing and description
of algorithm commonly used in mobile robotics. Chapter four contains overview of existing
solutions. On the grounds of literature review, two algorithms were chosen for the further
development. The thesis describes two variants of system implementation, first based on
Lucas-Kanade algorithm, second based on CAMShift method. This variants are described in
chapter seven and eight. The methodology of selection is described in chapter six, which also
contains general project assumptions.

## Sources

<table id="qs_table" border="1">
<thead><tr><th width="20%">Author</th><th width="30%">Title</th><th width="5%">Year</th><th width="30%">Journal/Proceedings</th><th width="10%">Reftype</th><th width="5%">DOI/URL</th></tr></thead>
<tbody><tr id="Allen2006" class="entry">
	<td>Allen, J.G., Xu, R.Y.D. and Jin, J.S.</td>
	<td>Object tracking using CamShift algorithm and multiple quantized feature spaces</td>
	<td>2006</td>
	<td><br/>Vol. 36Proceedings of the Pan-Sydney area workshop on visual information processing, pp. 3 - 7&nbsp;</td>
	<td>inproceedings</td>
	<td>&nbsp;</td>
</tr>
<tr id="Baker2004" class="entry">
	<td>Baker, S. and Matthews, I.</td>
	<td>Lucas-Kanade 20 Years On: A Unifying Framework</td>
	<td>2004</td>
	<td>International Journal of Computer Vision<br/>Vol. 56(3), pp. 221-255&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1023/B:VISI.0000011205.11775.fd">DOI</a> &nbsp;</td>
</tr>
<tr id="Baker2011" class="entry">
	<td>Baker, S., Scharstein, D., Lewis, J.P., Roth, S., Black, M.J. and Szeliski, R.</td>
	<td>A Database and Evaluation Methodology for Optical Flow</td>
	<td>2011</td>
	<td>International Journal of Computer Vision<br/>Vol. 92(1), pp. 1 - 31&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1007/s11263-010-0390-2">DOI</a> &nbsp;</td>
</tr>
<tr id="Bouguet2000" class="entry">
	<td>Bouguet, J.-Y.</td>
	<td>Pyramidal implementation of the Lucas Kanade feature tracker - Description of the algorithm</td>
	<td>2000</td>
	<td>&nbsp;</td>
	<td>techreport</td>
	<td>&nbsp;</td>
</tr>
<tr id="Bradski1998" class="entry">
	<td>Bradski, G.R.</td>
	<td>Real time face and object tracking as a component of a perceptual user interface</td>
	<td>1998</td>
	<td>Fourth IEEE Workshop Applications of Computer Vision (WACV), pp. 214 - 219&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/ACV.1998.732882">DOI</a> &nbsp;</td>
</tr>
<tr id="Challa2011" class="entry">
	<td>Challa, S., Morelande, M.R., Mušicki, D. and Evans, R.J.</td>
	<td>Fundamentals of Object Tracking</td>
	<td>2011</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td><a href="http://dx.doi.org/10.1017/CBO9780511975837">DOI</a> &nbsp;</td>
</tr>
<tr id="Chaumette2006" class="entry">
	<td>Chaumette, F. and Hutchinson, S.</td>
	<td>Visual servo control. I. Basic approaches</td>
	<td>2006</td>
	<td>IEEE Robotics &amp; Automation Magazine<br/>Vol. 13(4), pp. 82 - 90&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1109/MRA.2006.250573">DOI</a> &nbsp;</td>
</tr>
<tr id="Chou2012" class="entry">
	<td>Chou, Y.-C. and Huang, B.-S.</td>
	<td>Mono vision particle filter based object tracking with a mobile robot</td>
	<td>2012</td>
	<td>IEEE/ASME International Conference on Mechatronics and Embedded Systems and Applications (MESA), pp. 87 - 92&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/MESA.2012.6275542">DOI</a> &nbsp;</td>
</tr>
<tr id="Comaniciu1999" class="entry">
	<td>Comaniciu, D. and Meer, P.</td>
	<td>Mean shift analysis and applications</td>
	<td>1999</td>
	<td><br/>Vol. 2The Proceedings of the Seventh IEEE International Conference on Computer Vision, pp. 1197 - 1203&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/ICCV.1999.790416">DOI</a> &nbsp;</td>
</tr>
<tr id="Comaniciu2003" class="entry">
	<td>Comaniciu, D., Ramesh, V. and Meer, P.</td>
	<td>Kernel-based object tracking</td>
	<td>2003</td>
	<td>IEEE Transactions on Pattern Analysis and Machine Intelligence<br/>Vol. 25(5), pp. 564 - 577&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1109/TPAMI.2003.1195991">DOI</a> &nbsp;</td>
</tr>
<tr id="Exner2010" class="entry">
	<td>Exner, D., Bruns, E., Kurz, D., Grundhöfer, A. and Bimber, O.</td>
	<td>Fast and robust CAMShift tracking</td>
	<td>2010</td>
	<td>IEEE Computer Society Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), pp. 9 - 16&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/CVPRW.2010.5543787">DOI</a> &nbsp;</td>
</tr>
<tr id="Forsyth2012" class="entry">
	<td>Forsyth, D.A. and Ponce, J.</td>
	<td>Computer Vision - A modern approach</td>
	<td>2012</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td>&nbsp;</td>
</tr>
<tr id="Hartley2004" class="entry">
	<td>Hartley, R. and Zisserman, A.</td>
	<td>Multiple View Geometry in Computer Vision</td>
	<td>2004</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td>&nbsp;</td>
</tr>
<tr id="Horn1981" class="entry">
	<td>Horn, B.K.P. and Schunck, B.G.</td>
	<td>Determining Optical Flow</td>
	<td>1981</td>
	<td>Artificial Intelligence<br/>Vol. 17, pp. 185 - 203&nbsp;</td>
	<td>article</td>
	<td>&nbsp;</td>
</tr>
<tr id="Jaehne2005" class="entry">
	<td>Jähne, B.</td>
	<td>Digital Image Processing</td>
	<td>2005</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td>&nbsp;</td>
</tr>
<tr id="Karasulu2013" class="entry">
	<td>Karasulu, B. and Korukoglu, S.</td>
	<td>Performance Evaluation Software - Moving Object Detection and Tracking in Video</td>
	<td>2013</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td><a href="http://dx.doi.org/10.1007/978-1-4614-6534-8">DOI</a> &nbsp;</td>
</tr>
<tr id="Kim2011" class="entry">
	<td>Kim, K.-s., Bahn, W., Lee, C., Lee, T.-j., Shaikh, M. and Kim, K.-s.</td>
	<td>Vision system for mobile robots for tracking moving targets, based on robot motion and stereo vision information</td>
	<td>2011</td>
	<td>IEEE/SICE International Symposium on System Integration, pp. 634 - 639&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/SII.2011.6147522">DOI</a> &nbsp;</td>
</tr>
<tr id="Kim2012" class="entry">
	<td>Kim, T.-I., Bahn, W., Lee, C.-H., Lee, T.-J., Jang, B.-M., Lee, S.-H., Moon, M.-W. and Cho, D.-I.</td>
	<td>A Robotic Pan and Tilt 3-D Target Tracking System by Data Fusion of Vision, Encoder, Accelerometer, and Gyroscope Measurements</td>
	<td>2012</td>
	<td>Intelligent Robotics and Applications - 5th International Conference, pp. 676-685&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1007/978-3-642-33515-0_66">DOI</a> &nbsp;</td>
</tr>
<tr id="Liem2008" class="entry">
	<td>Liem, M., Visser, A. and Groen, F.</td>
	<td>A hybrid algorithm for tracking and following people using a robotic dog</td>
	<td>2008</td>
	<td>Proceedings of the 3rd ACM/IEEE international conference on Human robot interaction, pp. 185-192&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1145/1349822.1349847">DOI</a> &nbsp;</td>
</tr>
<tr id="Lowe2004" class="entry">
	<td>Lowe, D.G.</td>
	<td>Distinctive Image Features from Scale-Invariant Keypoints</td>
	<td>2004</td>
	<td>International Journal of Computer Vision<br/>Vol. 60(2), pp. 91 - 110&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1023/B:VISI.0000029664.99615.94">DOI</a> &nbsp;</td>
</tr>
<tr id="Markovic2014" class="entry">
	<td>Marković, I., Chaumette, F. and Petrović, I.</td>
	<td>Moving object detection, tracking and following using an omnidirectional camera on a mobile robot</td>
	<td>2014</td>
	<td>IEEE International Conference on Robotics and Automation, pp. 5630 - 5635&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/ICRA.2014.6907687">DOI</a> &nbsp;</td>
</tr>
<tr id="Olivares-Mendez2009" class="entry">
	<td>Olivares-Méndez, M.A., Campoy, P., Martínez, C. and Mondragón, I.</td>
	<td>A pan-tilt camera Fuzzy vision controller on an unmanned aerial vehicle</td>
	<td>2009</td>
	<td>IEEE/RSJ International Conference on Intelligent Robots and Systems, pp. 2879 - 2884&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/IROS.2009.5354576">DOI</a> &nbsp;</td>
</tr>
<tr id="Shi1994" class="entry">
	<td>Shi, J. and Tomasi, C.</td>
	<td>Good features to track</td>
	<td>1994</td>
	<td>Computer Society Conference on Computer Vision and Pattern Recognition (CVPR), pp. 593 - 600&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/CVPR.1994.323794">DOI</a> &nbsp;</td>
</tr>
<tr id="Smeulders2010" class="entry">
	<td>Smeulders, A.W.M., Chu, D.M., Cucchiara, R., Calderara, S., Dehghan, A. and Shah, M.</td>
	<td>Visual Tracking: An Experimental Survey</td>
	<td>2010</td>
	<td>IEEE Transactions on Pattern Analysis and Machine Intelligence<br/>Vol. 36IEEE Transactions on Pattern Analysis and Machine Intelligence, pp. 1442 - 1468&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1109/TPAMI.2013.230">DOI</a> &nbsp;</td>
</tr>
<tr id="Szeliski2011" class="entry">
	<td>Szeliski, R.</td>
	<td>Computer Vision - Algorithms and Applications</td>
	<td>2011</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td>&nbsp;</td>
</tr>
<tr id="Tomasi1991" class="entry">
	<td>Tomasi, C. and Kanade, T.</td>
	<td>Detection and Tracking of Point Features</td>
	<td>1991</td>
	<td>(CMU-CS-91-132)&nbsp;</td>
	<td>techreport</td>
	<td>&nbsp;</td>
</tr>
<tr id="Treiber2010" class="entry">
	<td>Treiber, M.A.</td>
	<td>An Introduction to Object Recognition - Selected Algorithms for a Wide Variety of Applications</td>
	<td>2010</td>
	<td>&nbsp;</td>
	<td>book</td>
	<td>&nbsp;</td>
</tr>
<tr id="Welch1995" class="entry">
	<td>Welch, G. and Bishop, G.</td>
	<td>An Introduction to the Kalman Filter</td>
	<td>1995</td>
	<td>&nbsp;</td>
	<td>techreport</td>
	<td>&nbsp;</td>
</tr>
<tr id="Yilmaz2006" class="entry">
	<td>Yilmaz, A., Javed, O. and Shah, M.</td>
	<td>Object Tracking: A Survey</td>
	<td>2006</td>
	<td>ACM Computing Surveys<br/>Vol. 38(4), pp. 1-45&nbsp;</td>
	<td>article</td>
	<td><a href="http://dx.doi.org/10.1145/1177352.1177355">DOI</a> &nbsp;</td>
</tr>
<tr id="Zhang2011" class="entry">
	<td>Zhang, Z., Sa, R. and Wang, Y.</td>
	<td>A real time object tracking approach for mobile robot visual servo control</td>
	<td>2011</td>
	<td>First Asian Conference on Pattern Recognition (ACPR), pp. 500 - 504&nbsp;</td>
	<td>inproceedings</td>
	<td><a href="http://dx.doi.org/10.1109/ACPR.2011.6166627">DOI</a> &nbsp;</td>
</tr>
</tbody>
</table>
<small>Created by <a href="http://jabref.sourceforge.net">JabRef</a> on 06/02/2017.</small>