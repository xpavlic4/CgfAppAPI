# CgfAppAPI
APIs called from the CGF android app

http://server.cgf.cz:8010/mobile/CGFMobile.svc/FindGolfer?searchString=radim
<pre>
{
   "Message":"",
   "ResultCode":"SUCCESS",
   "ResultError":0,
   "Golfers":[
      {
         "Blocked":"N",
         "ClubName":"Golf Club Grabštejn",
         "GolferName":"RADIM Kolář Ing. ",
         "Hcp":"54",
         "IdGolfer":306898097,
         "MemberNumber":"0720252",
         "ValidFrom":1280966400,
         "ValidTo":1282608000
      },
      {
         "Blocked":"N",
         "ClubName":"Klub hráčů golfu České Švýcarsko",
         "GolferName":"RADIMECKÁ Ivana Mgr. ",
         "Hcp":"17,7",
         "IdGolfer":74694784,
         "MemberNumber":"0700250",
         "ValidFrom":1486684800,
         "ValidTo":32503593600
      },
      {
         "Blocked":"N",
         "ClubName":"Klub hráčů golfu České Švýcarsko",
         "GolferName":"RADIMECKÝ Josef PhDr. Ph.D.,MSc.",
         "Hcp":"18,7",
         "IdGolfer":59335599,
         "MemberNumber":"0700136",
         "ValidFrom":1486684800,
         "ValidTo":32503593600
      },
      {
         "Blocked":"N",
         "ClubName":"Klub hráčů golfu České Švýcarsko",
         "GolferName":"RADIMECKÝ Josef Ing. ",
         "Hcp":"BEZ",
         "IdGolfer":438175824,
         "MemberNumber":"0700644",
         "ValidFrom":1413590400,
         "ValidTo":4102358400
      },
      {
         "Blocked":"Y",
         "ClubName":"Golf Club Hostivař",
         "GolferName":"RADIMSKÝ Radovan  ",
         "Hcp":"21,9",
         "IdGolfer":96870715,
         "MemberNumber":"0780146",
         "ValidFrom":1311120000,
         "ValidTo":1311206400
      }
   ]
}
</pre>

http://server.cgf.cz:8010/mobile/CGFMobile.svc/GetCourses
