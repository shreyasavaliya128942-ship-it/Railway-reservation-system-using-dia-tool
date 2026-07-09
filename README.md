ailway Reservation System — OOAD Project

An Object-Oriented Analysis and Design (OOAD) project modeling a Railway Reservation System using standard UML diagrams. The project covers the full booking lifecycle — from route search and seat selection to payment and confirmation — and documents the system's structure, behavior, and deployment through UML.

📋 Overview

The system allows a User to search routes, select a coach and seat, make a payment, and receive a booking confirmation, while an Admin manages routes, coaches, and seat layouts. Key entities modeled include:


User — UserID, Name, Email, MobileNo
Booking — BookingID, PNR, Date, Status
Coach — CoachID, CoachType, Capacity
Seat — SeatNo, SeatType, Availability
Route — RouteID, Source, Destination, Distance
Payment — TransactionID, Mode, Amount, Status
Notification — MessageID, Type, Status


Actors


User — search route, choose seat, book coach, cancel booking, receive notification
Admin — add route, manage coach, update seat layout, send notifications
Payment Gateway — process payment, refund


📊 UML Diagrams

All diagrams are provided both as editable Dia source files (.dia) and rendered PNG images (DIAGRAMS_FINAL_PICTURES/).

DiagramSource FileRendered ImageClass Diagramclass diagram FINAL.diaCLASS_DIAGRAM_FINAL.pngObject DiagramOBJECT.diaOBJECT_DIAGRAM_FINAL.pngUse Case DiagramUsecase_fINAL.diaUSECASE_DIAGRAM_FINAL.pngSequence DiagramSequence_final.diaSEQUENCE_DIAGRAM_FINAL.pngState DiagramSTATE_FINAL.diaSTATE_DIAGRAM_FINAL.pngActivity DiagramACTIVITY_FINAL(1).diaACTIVITY_DIAGRAM_FINAL.pngCollaboration Diagramcollaboration_f.diaCOLLABORATION_DIAGRAM_FINAL.pngComponent Diagramcomponent_F.diaCOMPONENT_DIAGRAM_FINAL.pngPackage DiagramPACKAGE_F.diaPACKAGE_DIAGRAM_FINAL.pngDeployment DiagramDeployment.diaDEPLOYMENT_DIAGRAM_FINAL.png

Diagram Highlights


Class Diagram — Core entities (User, Booking, Coach, Seat, Route, Notification) with attributes, operations, and relationships.
Object Diagram — A snapshot instance showing a user booking a confirmed seat on a specific route (e.g., Ahmedabad → Delhi).
Use Case Diagram — Interactions between User, Admin, and Payment Gateway actors.
Sequence Diagram — End-to-end booking flow: select route → choose coach/seat → lock seat → pay → confirm → notify.
State Diagram — Seat lifecycle: Available → Reserved → Confirmed → Occupied → Released.
Activity Diagram — Booking workflow: Login → Search Route → Select Coach → Choose Seat → Payment → Confirmation → Notify.
Deployment Diagram — Nodes: User Device, Reservation Server, Database Server, SMS Gateway, Payment Gateway.
Component Diagram — Modules: UI, Booking Manager, Seat Allocation Engine, Route Scheduler, Notification Service, Payment Processor, Database Access.
Package Diagram — Grouped into User Management, Booking System, Route Management, and Payment System packages.


📁 Repository Structure

OOAD PROJECT/
├── README.md
├── OOAD RAILWAY RESERVATION SYSTEM PROJECT.docx   # Design notes & diagram descriptions
├── Railway Reservation System (1).pptx            # Project presentation
├── BSc(DS)-3 Presentation Groups.xlsx              # Group/presentation schedule
├── *.dia                                           # Editable UML source files (Dia)
└── DIAGRAMS_FINAL_PICTURES/
    ├── BSc(DS) - 3 UML Report(Group-4).docx        # Final UML report
    └── *_DIAGRAM_FINAL.png                         # Rendered UML diagram images

🛠️ Tools Used


Dia — UML diagram editor (.dia files)
Microsoft Word / Office — project report and documentation
Microsoft PowerPoint — presentation


🚀 Viewing the Diagrams


Quick view: open any PNG in DIAGRAMS_FINAL_PICTURES/.
To edit: open the corresponding .dia file in Dia (free, cross-platform).


👥 Academic Info

This project was prepared as part of a BSc (Data Science) OOAD coursework assignment (Group 4).

📄 License

Academic project — for educational purposes.
