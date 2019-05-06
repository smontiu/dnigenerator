# dnigenerator
Spanish DNI (National Document Identification) generator, perfect for OCR testing

# Motivation
At work we have multiple situations working with a third party OCR and we want an easy way to not only unit test our logics but also test all the flow (e2e) using different generated images.
Automate the process to obtain the base64 blob to send it with different presets (css transformations) (rotate, scaled, color black & white, sepia, ...)