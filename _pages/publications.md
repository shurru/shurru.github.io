---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Palaniappan, SM, Suresh, S, Haddad, J.M, & Duerstock, B. S. (2020). Adaptive Virtual Reality Exergame for Individualized Rehabilitation for Persons with Spinal Cord Injury. In Proceedings of the European Conference on Computer Vision (ECCV) Workshops. 
Suresh, S., & Duerstock, B. S. (2020). Automated Detection of Symptomatic Autonomic Dysreflexia through Multimodal Sensing, In IEEE Journal of Translational Engineering in Health and Medicine
Suresh, S., Everett, T. H., Li, J., Walls, E. K., & Duerstock, B. S. (2019). Sensing Sympathetic Activation Using Novel Non-Invasive Techniques in Rats. In 2019 IEEE SENSORS (pp. 1-4). IEEE.
Suresh, S., & Duerstock, B. S. (2018). Optimal Feature Selection for the Detection of Autonomic Dysreflexia in Individuals with Tetraplegia. In 2018 IEEE International Symposium on Signal Processing and Information Technology (ISSPIT) (pp. 480-485). IEEE.
Suresh, S.; Manda S., Marrero C., Jacob L. & Duerstock B. (2017). Multi-functional Wrist Orthotic with Universal Gesture Recognition System. In Proceedings of the Rehabilitation Engineering Society of North America Annual Conference 2017.
	Suresh, S; Raftery, B.; Duerstock, B. (2017). Detection of Autonomic Dysreflexia in persons with Cervical Spinal Cord Injuries through a Support Vector Machine. In Proceedings of the Rehabilitation Engineering Society of North America Annual Conference 2017.
Suresh S., Raftery B. & Duerstock B. (2016). Wearable Physiological Telemetry for Individuals with Spinal Cord Injuries to Self-Monitor Secondary Health Complications. In Proceedings of the Rehabilitation Engineering Society of North America Annual Conference 2016.
Suresh S., Chiquito DFM., Manda S., Jacob L. & Duerstock B. (2016). Motor Activated Multi-Functional Wrist Orthotic to Assist Individuals with Cervical Spinal Cord Injuries with Activities of Daily Living. In Proceedings of the Rehabilitation Engineering Society of North America Annual Conference 2016. 
Suresh S., Duerstock H., & Duerstock B.  (2015). Skin Resistance as a Physiological Indicator for Quadriplegics with Spinal Cord Injuries During Activities of Daily Living. In Smart Health (pp. 157-168). Springer International Publishing.
Suresh S, Liu Y, Yeow CH (2015). Development of a Wearable Electroencephalographic Device for Anxiety Monitoring. ASME Journal of Medical Devices. 
Suresh, S, & Yeow, CH. (2014). Detection of anxiety through analysis of occipital EEG. In Proceedings of the International Convention on Rehabilitation Engineering & Assistive Technology (p.  3).  Singapore Therapeutic, Assistive & Rehabilitative Technologies (START) Centre.
Cabibihan, J. J., Chauhan, S. S., & Suresh, S. (2014). Effects of the artificial skin's thickness on the subsurface pressure profiles of flat, curved, and Braille surfaces. IEEE Sensors Journal, 14(7), 2118-2128.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
