# ExtVid
**ExtVid** is the tool for **immersive video experience** using OpenCV.


Immersion for viewing video is strongly related with FoV (Field of View).
>"When a viewer’s entire field of view is filled, it creates a more immersive experience, increasing their enjoyment of the content."
>L. Turban, F. Urban and P. Guillotel, "Extrafoveal Video Extension for an Immersive Viewing Experience," in IEEE Transactions on Visualization and Computer Graphics, vol. 23, no. 5, pp. 1520-1533, 1 May 2017, doi: [10.1109/TVCG.2016.2527649](10.1109/TVCG.2016.2527649)


But view angle of content should be under 45 angle, because of limitation of human fovea.
>"The ideal picture size is defined for movie theatre for a horizontal viewing angle of 45 degrees at the prime seat."
>Lee YC.N., Shan LT., Chen CH. (2013) System Development of Immersive Technology Theatre in Museum. In: Shumaker R. (eds) Virtual, Augmented and Mixed Reality. Systems and Applications. VAMR 2013. Lecture Notes in Computer Science, vol 8022. Springer, Berlin, Heidelberg. doi: [https://doi.org/10.1007/978-3-642-39420-1_42](https://doi.org/10.1007/978-3-642-39420-1_42)*


So best solution for immersive video experience is extending video by context matched image, as below.

![Before_After](/img/before_after.jpg)

## Requirement
- Resolution can be divided by 4 (e.g. 1280x720)
