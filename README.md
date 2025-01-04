        $telegramBotApi->sendPaidMedia([
            'chat_id' => <chat_id>,
            'media' => json_encode([
                [
                    'type' => 'photo',
                    'media' => $file1,
                ],
                [
                    'type' => 'photo',
                    'media' => $file2,
                ]
            ]),
            'star_count' => 1,
        ]);