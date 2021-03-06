# SimpleTimeline

A flutter package that allows you to create basic timelines on your flutter application. This is customizable and easy to plugin to your application. You will find the following features:

* A simple timeline with a title and a description
* Customizable color options for - Line, Title, Description and Background
* Tween animation on the line

<image src="https://github.com/zapiti/simple_timeline/blob/main/simple_timeline.jpeg" height="300em"/>

## Getting Started

You will need to add the following dependency in your `pubspec.yaml` file to download the depedency.

```dart
dependencies:
  flutter:
    sdk: flutter
  simple_timeline: 1.0.1
```


## Usage

> import 'package:simple_timeline/simple_timeline.dart';


```
   SimpleTimeLine(timelineList: [
            TimelineEntity(
                enable: true,
                description: "Lorem Ipsum",
                title: "Lorem Ipsum"),
            TimelineEntity(
                enable: true,
                description: "Lorem Ipsum",
                title: "Lorem Ipsum"),
            TimelineEntity(
                enable: true,
                description: "Lorem Ipsum",
                title: "Lorem Ipsum"),
            TimelineEntity(enable: false, title: "Lorem Ipsum"),
            TimelineEntity(
                enable: false,
                title: "Lorem Ipsum",
                description:
                'It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.',
                disableColor: Colors.red)
          ]),
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

